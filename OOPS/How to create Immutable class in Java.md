Immutable class in java means that once an object is created, we cannot change its content. In Java, all the [wrapper classes] (like Integer, Boolean, Byte, Short) and String class is immutable.

- The class must be declared as final so that child classes can’t be created.
- Data members in the class must be declared private so that direct access is not allowed.
- Data members in the class must be declared as final so that we can’t change the value of it after object creation.
- A parameterized constructor should initialize all the fields performing a deep copy so that data members can’t be modified with an object reference.
- Deep Copy of objects should be performed in the getter methods to return a copy rather than returning the actual object reference.
