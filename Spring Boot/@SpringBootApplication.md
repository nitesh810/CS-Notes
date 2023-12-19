
### What does the @SpringBootApplication annotation do internally?

- The @SpringBootApplication annotation is equivalent to using `@Configuration`, `@EnableAutoConfiguration`, and `@ComponentScan. 
- Spring Boot enables the developer to use a single annotation instead of using multiple.
- Spring provided loosely coupled features.


- ***@Configuration***
	Configure the class as a ***Bean,*** which are objects that are created and managed by the Spring container. 
	
- ***@ComponentScan***
	The `@ComponentScan` annotation is used to enable component scanning in your application.
	Scans all the classes that are annotated by ***Stereotype annotations.***
	
- ***@EnableAutoConfiguration***
	Enables the mechanism of auto configuration in spring boot. 
	When you annotate a class with `@EnableAutoConfiguration`, Spring Boot will automatically configure the application based on its dependencies.


## Basic Annotations that Spring Boot Offers

@SpringBootApplication – combines @Configuration, @EnableAutoConfiguration, and @ComponentScan annotations with their default attributes.
@RestController