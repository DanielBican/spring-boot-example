# spring-boot-example
Example of a spring boot project that connects to the MySQL database locally

# To build the jar run the command:
(from the root of your project)
```bash
mvnw install
```

# To run the application:
* From the command line
```bash
java -jar target\spring-boot-example-0.0.1-SNAPSHOT.jar <coinType> <amount>
```
* From IntelliJ IDEA:
Make sure that you will configure arguments for the application

![SpringBootExampleApplication drop down -> Edit Configurations -> Program arguments](https://github.com/DanielBican/spring-boot-example/blob/master/configure-program-arguments.PNG)
