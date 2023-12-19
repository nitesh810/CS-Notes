Super is used to access parent class methods and attributes from the child class's scope.

The super keyword in Java is a reference variable which is used to refer to an immediate parent class object.

Whenever you create an instance of a subclass, an instance of the parent class is created implicitly which is referred to by a super reference variable.


⚠ Note the super constructor should be called before any initialization of the child class members.
```
public Car(int price,int milage,String fuelType,String manufacturer,int tax){  
    super(4,5,price,milage);  
    this.fuelType = fuelType;  
    this.manufacturer = manufacturer;  
    this.tax = tax;  
}
```