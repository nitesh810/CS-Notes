
- Stereotype annotations are also beans in Spring Boot. ( ***Class level bean*** )
- Stereotype annotations are special annotations that provide metadata about a class and are used to create Spring beans automatically in the application context. 
- special annotations that can be used to mark classes as having a particular role or purpose within the application.
- Some of the most commonly used stereotype annotations are @Component, @Service, @Repository, @RestController.
- When a class is annotated with a stereotype annotation, Spring Boot automatically creates a bean instance of that class and registers it in the application context.

#### Note : Inside of ***@Service & @Repository*** -> @Component is there
#### Spring only creates object when there is @Component annotation have directly or indirectly and put inside IoC Container