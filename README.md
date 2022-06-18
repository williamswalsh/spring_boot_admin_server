# spring_boot_admin_server
This is a demo of the Spring Boot Admin server. \
This app can be used to represent metrics in a visual fashion. \
Multiple client apps can be monitored from this single "admin server". \
This app is running on port 8081. \
This app will interact with the actuator_project. 

### Execution
```shell
# Change JDK to version 11
jdk11

# Clean, compile and execute the app
mvn clean compile spring-boot:run
```