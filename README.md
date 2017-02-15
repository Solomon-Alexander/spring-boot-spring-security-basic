# spring-boot-spring-security-basic
Application to demonstrate spring boot with spring basic security

Build and run the application

Prerequisites:

1. Install JDK 8.
2. Install Maven 3.3.9.


The spring-boot-spring-security-basic project can be build and run with the below steps:

1. Go to Project directory.
2. Run mvn clean install.
3. Run mvn spring-boot:run to run the spring-boot-spring-security-basic app using the Spring Boot Embedded Tomcat Container.
4. Application will be running and tested using http://localhost:8081
5. Login using john_kennedy@gmail.com/123456aA

Note: Currently the tomcat will be running in port 8081, if there are conflicting ports, then
change the property "server.port" from the application.properties located in src/main/resources.


