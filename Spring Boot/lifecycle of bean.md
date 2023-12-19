The lifecycle is managed by the Spring Boot container.

**The bean lifecycle can be divided into four phases:**
1. Instantiation: The Spring Boot container creates an instance of the bean.
2. Initialization: The Spring Boot container injects any dependencies that the bean has.
3. Usage: The bean is available to be used by other beans in the Spring Boot application.
4. Destruction: The Spring Boot container destroys the bean when it is no longer needed.