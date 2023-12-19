### How to connect Spring Boot application to database using JDBC?
**Spring Boot JDBC** provides starter and libraries for connecting an application with JDBC.

you need to add required dependencies that are provided by spring-boot to connect your application with JDBC.

**Step 1**: First create a database in MySQL with create DATABASE student;
**Step 2**:  Now, create a table inside this DB:  
**Step 3**: Create a spring Boot and add JDBC, mysql and web dependencies.  
**Step 4**: In application.properties, you need to configure the database.
**Step 5**: In your controller class, you need to handle the requests.
**Step 6**: Run the application and check the entry in your Database.
**Step 7**: You can also go ahead and open the URL and you will see “Data Entry Successful” as your output.

**Dependency name :** Spring Data JDBC

### How to connect Spring Boot to the database using JPA?
Spring Boot provides ***spring-boot-starter-data-jpa*** starter to connect Spring application with relational database efficiently. You can use it into project POM (Project Object Model) file.

**Spring Boot JPA** is a Java specification for managing **relational** data in Java applications.
- Java Persistence API
- JPA follows **Object-Relation Mapping** (ORM).
- It is a set of interfaces.
- It also provides a runtime **EntityManager** API for processing queries and transactions.
- JPA is not a framework. It defines a concept that can be implemented by any framework.
- JPA allows us to avoid writing Queries.

### Hibernate
- Hibernate is a framework.
- Hibernate is an **object-relational mapping (ORM)** framework that basically allows a developer to map objects to relational database tables.
- Hibernate gives the implementation of JPA.

## JpaRepository
- JPA repository extends ***CrudRepository*** and ***PagingAndSortingRepository***.
- JpaRepository is a **JPA (Java Persistence API)** extension of Repository.
- Contains API for basic CRUD operations and also API for pagination and sorting.