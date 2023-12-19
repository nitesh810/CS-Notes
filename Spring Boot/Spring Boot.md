
## Definition

- ***Spring Boot***
	Sprint boot is a Java-based spring framework used for Rapid Application Development (to build stand-alone microservices). It has extra support of auto-configuration and embedded application servers like tomcat, jetty, etc.
- ***Microservice****
	Microservices is a software development approach that uses a collection of small, independent services to build a large application.

## Features of Spring Boot that make it different?

- Creates stand-alone spring application with minimal configuration needed.
- It has embedded tomcat, jetty which makes it just code and run the application.
- Provide production-ready features such as metrics, health checks, and externalized configuration.
- Absolutely no requirement for XML configuration.

### Advantages of using Spring Boot?

- Easy to understand and develop spring applications.
- Spring Boot is nothing but an existing framework with the addition of an embedded HTTP server and annotation configuration which makes it easier to understand and faster the process of development.
- Increases productivity and reduces development time.
- Minimum configuration.
- We don’t need to write any XML configuration, only a few annotations are required to do the configuration.

### Spring Boot key components?

Below are the four key components of spring-boot:

- Spring Boot auto-configuration.
- Spring Boot CLI.
- Spring Boot starter POMs.
- Spring Boot Actuators.

### Why Spring Boot over Spring?

Below are some key points which spring boot offers but spring doesn’t:

- Starter POM.
- Version Management.
- Auto Configuration.
- Component Scanning.
- Embedded server.
- InMemory DB.
- Actuators

-> **InMemory DB** : In-memory databases are a type of database that stores data in the main memory or RAM of a computer. This makes them very fast, as there is no need to access disk drives.


### How does Spring Boot works?

Spring Boot automatically configures your application based on the dependencies you have added to the project by using annotation. The entry point of the spring boot application is the class that contains @SpringBootApplication annotation and the main method.

### what is bean in spring
A bean is an object that is instantiated, assembled, and managed by a Spring IoC container.