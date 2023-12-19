- ***@Entity***
	Specifies that the class is an entity and is mapped to a database table.
	
- ***@GeneratedValue(strategy = GeneratedType.Identity)***
	Is used to indicate that the database will automatically generate primary key values.
	
- ***@Id***
	Specifies the primary key of an entity.
	
- ***@Column(unique = true)***
	To specifies that column is unique.
	
- ***@Enumerated(EnumType.STRING)***
	- To map an Enum to a String database column type.
	- In JPA, an enum is a value like String or Integer. Users can map it on the DB as Integer ( @Enumerated(ORDINAL) ) or as String ( @Enumerated(STRING) ).
	
- ***@OneToMany(mappedBy = "person",cascade = CascadeType.ALL)***
	- _mappedBy_ is an attribute of _@OneToMany_ annotation, Specifies the column name that which its connected.
	- **"CascadeType.ALL"** is used to propagate all operations from a parent to a child entity.
	
- ***@JoinColumn***
	Used in child class to connect with parent class.
	
- ***@FieldDefaults(level = AccessLevel.PRIVATE)***
	It is a **lombok** annotation to make all variables private. ( Lombok is a Dependency )
	
- ***@CreationTimestamp***
	to track the timestamp of the creation and last update of an entity.


### How to create Spring Boot application using Maven?
- Spring Initializer
- Spring Boot CLI

### How to create Spring Boot project using boot CLI?
- It is a tool which you can download from the official site of Spring Framework.
- After downloading, extract the zip file. It contains a bin folder, in which spring setup is stored.
- CLI executes groovy files. So, first, we need to create a groovy file for Spring Boot application.

### **How to insert data in mysql using spring boot?**
First configure mysql in your spring boot application.

Then you can map your entities with your db tables using JPA.

And with the help of save() method in JPA, you can directly insert your data into your database.


### What is the main class in spring boot?
Usually in java applications, a class that has a main method in it is considered as a main class. Similarly, in spring boot applications main class is the class which has a public static void main() method and which starts up the SpringApplicationContext.

### How to handle 404 error in spring boot?
By creating custom Exceptions.

### Which is the spring boot latest version?
3.1.5

### Can we override or replace the embedded tomcat server in spring boot?
Spring boot by default comes up with the embedded server once we add the “Spring –boot-starter” dependency.
If we don’t want to use the tomcat, then tomcat comes with three types of embed servers: Tomcat, jetty, and undertow.

