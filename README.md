# spring-resourceserver

Spring resource service using spring-boot-starter-oauth2-resource-server library.

This project use as authentication server the project https://github.com/abisai7/spring-authserver.git, 
you can use it as authentication service cloning and executing before executing this project.

## Requirements

- Java Development Kit (JDK) 17 or higher
- Gradle

## Installation and Execution

1. Clone the repository:

```bash
git clone https://github.com/abisai7/spring-resourceserver.git
````

2. Navigate to the project directory:

```bash
cd spring-resourceserver
```

3. Run the application:Use Gradle Wrapper (gradlew) to compile and run the project:

```bash
./gradlew bootRun
```

This will start the Spring Boot application. Once you see a message in the console indicating that the application has started successfully, you can access test making a request to endpoints defined in controllers.


