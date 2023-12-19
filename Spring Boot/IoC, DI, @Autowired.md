
#### Inversion means Reverse.
#### Inversion of Control means spring takes care of bean creation.
### IoC

On the starting of the application at that time spring creates object of class have having annotation like @Component directly or indirectly and put inside of IoC container.

If IoC container don't creates the object, every time when API calls objects get created using new keyword and memory will take every time.
#### Note : Object creation is only happen once.


### DI (Dependency Injection)
Injecting the beans from IoC container to the class.
You can achieve y using @Autowired annotation.

- **Setter Injection:** The IOC container will inject the dependent bean object into the target bean object by calling the setter method.
- **Constructor Injection:** The IOC container will inject the dependent bean object into the target bean object by calling the target bean constructor.
- **Field Injection:** The IOC container will inject the dependent bean object into the target bean object by Reflection API.

### @Autowired
Autowired helping you to use the beans.
Autowired is not creating Instance.
Autowired is connecting the object to the class.
Object is creating is taken care by spring.
Object are called beans.