
The static variable gets memory only once in the class area at the time of class loading. 

The ​static keyword​ in ​Java​ is used for memory management mainly. We can apply static keyword with ​variables​, methods, blocks and ​nested classes​. The static keyword belongs to the class rather than an instance of the class.

-------------------------------------------------------------------------------

### Static Function

- If you apply a static keyword with any method, it is known as static method.
- A static method belongs to the class rather than the object of a class.
- A static method can be invoked without the need for creating an instance of a class.
- A static method can access static data members and can change the value of it.

-------------------------------------------------------------------------------


- **non-static members/methods  cannot be accessed in the static context**
	- because static methods do not need any instance of an object, whereas non-static member/methods, need  instance  of an object
- static member/methods can be accessed in an non static context.
- Static members are called by Class name itself
	- `Human.population` where `Human` is the className not the instance variable name.
- [[this keyword]] keyword doesn't work
- Initialization?  Static block
	- Inner static class?
- #### Why is `public static void main` static?
	- Main method has to be declared static because keyword static allows main to be called without creating an object of the class in which the main method is defined.
- How to access non static methods inside static methods
```
public static void printSubjects(){  
    Student rohan = new Student("Rohan",20,30);  
    rohan.setName("Vikas");  //setName -> non static
    for(String s: subjects){  
        System.out.print(s+", ");  
    }  
}
```
- [[Inner classes]]- Static depends on the Scope of where its  written.
- A nested static member will be static/independent of the initialization of all the nester classes.
```
public class Main {  
    public class Car{  
        static String manufacturer="ABC";  
        int price;  
  
        public Car(String manufacturer, int price) {  
            this.manufacturer = manufacturer;  
            this.price = price;  
        }  
    }  
  
    public static void main(String[] args) {  
        System.out.println(Main.Car.manufacturer);  
    }  
}
```
`manufacturer` is static, not only for Car but also for main.