Polymorphism is composed of two words - “poly” which means “many”, and “morph” which means “shapes”. Therefore Polymorphism refers to something that has many shapes.

![[Pasted image 20231124094015.png]]

Polymorphism allows us to perform a single action in different ways. In other words, polymorphism allows you to define one interface and have multiple implementations.

**In Java polymorphism is mainly divided into two types:** 
● Compile time Polymorphism ( ***Static Binding*** )
● Runtime Polymorphism ( ***Dynamic Binding*** )

1. **Compile-time polymorphism :** It is also known as **Static polymorphism**. This type of polymorphism is achieved by Method overloading or operator overloading. **But Java doesn't supports the Operator Overloading.**
	
	 - **Method Overloading :** When there are multiple functions with the same name but different parameters then these functions are said to be overloaded.
	
2. **Runtime Polymorphism :** It is also known as Dynamic Method Dispatch. It is a process in which a function call to the overridden method is resolved at Runtime.
	
	- **Method Overriding :** It occurs when a "**derived class (Child class)**" has a definition for one of the member functions of the "**base class (Parent class)**". That base function is said to be overridden.

-------------------------------------------------------------------------------

Poly - many
morph - change shape

- Compile Time/ Static poly.
	- Method overloading.
		- 2 methods act differently, when the data types of parameters are diff
	- Operator overloading - **Java Doesn't support**
		- a = 10, b = 10;
		- a + b => 
- Runtime Poly/Dynamic poly
	- Method Overriding
		- [[@Override Annotation]]
		- The child class during runtime decides to ignore the implementation of same method from the parent class, giving priority of its own method
		- [[Upcasting or Dynamic method dispatch and Downcasting]]
		- You cannot override **final** methods
			- I don't want any tampering
			- Enhance compiler performance  for early binding, compiler during the compile time will decide that a final method will look same for every child.
```
public final void sayHello(){  
    System.out.println("Hello from the parent class");  
}
```
- Static methods can be inherited but cannot be overridden