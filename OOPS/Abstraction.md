- Hiding unnecessary details and showing the valuable information.
- We don't care about HOW, we just care about WHAT

### Abstract Class
Abstract Classes An abstract class can be considered as a blueprint for other classes. Abstract classes are classes that contain one or more abstract methods.
- By default, Java does not provide abstract classes.
- A method becomes abstract when decorated with the keyword ​abstract.
- An abstract class cannot be directly instantiated i.e. we cannot create an object of the abstract class.
- However, the subclasses of an abstract class that have definitions for all the abstract methods declared in the abstract class, can be instantiated.
- Making parent class, an abstract class and giving it some abstract methods will force any child class to implement those methods.
- Not complete Class.
- Some methods might be  implemented some might not be implemented, which are to implemented in the child class.

-------------------------------------------------------------------------------

**The given Java code uses the ​ABC​ class and defines an abstract base class:**

abstract class ABC { 
	int value; 
	Abstract int do_something() { 
		//Our abstract method declaration // TO_DO 
	} 	
}

class add extends ABC { 

	int do_something() { 
	return value + 42; 
	} 
}

-------------------------------------------------------------------------------

**Note:** ​Concrete classes contain only concrete (normal) methods whereas abstract classes may contain both concrete methods and abstract method


abstract class ABC { 
	abstract int do_something() { 
		//Abstract Method 
		System.out.println("Abstract Class AbstractMethod"); 
	} 
	int do_something2() { 
		//Concrete Method 
		System.out.println("Abstract Class ConcreteMethod"); 
		} 
} 

class AnotherSubclass extends ABC { 
	int do_something() { 
		//Invoking the Abstract method from super class 
		super().do_something(); 
	} 
	//No concrete method implementation in subclass 
}

class Test { 
	public static void main(String[] args) { 
		AnotherSubclass x = new AnotherSubclass() 
		x.do_something() 
		//calling abstract method 
		x.do_something2() 
		//Calling concrete method
	}
}