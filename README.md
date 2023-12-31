# Coffee-Buddy

## Your tasks today

Take your time to understand what this app is doing and try to get it running.
If there are any problems, try to fix them.
If there is bad code, feel free to refactor it.
Please tell us what you are doing and what your ideas are, so that we can follow you.
To run this app you need at least Java JDK 17 (or newer); alternatively, you can make use of the docker file.

## A couple of key points

This is not a test! There is no "master" solution. We just want to get an overall picture of you working with code.
Just pretend it is your first working day and this is your task. You can do everything you would normally do 
(including use Google, Stackoverflow or ask us for help).
This is supposed to be done in casual conversation, relax and tell us your opinion about the questions.
We do pair programming here and this interview is not different, so if there is anything you need help with, please ask.
You can use your favorite IDE.


## Technical Setup

- Spring Boot with embedded H2, Flyway, OpenAPI 3.0, Swagger, and Lombok
- Local Setup
  - Build
    - `./gradlew clean build`
  - Run
    - `java -jar ./build/libs/coffee-buddy-0.0.1-SNAPSHOT.jar`
- Container Setup
  - Build and Run
    - `docker build -t coffee-buddy . && docker run --rm -p 8080:8080 coffee-buddy`
- Links (localhost):
  - [localhost:8080](http://localhost:8080)
  - [API-Docs](http://localhost:8080/v3/api-docs)
  - [Swagger UI](http://localhost:8080/swagger-ui/index.html)

## Getting Started (Generated by Spring Initilizer)

### Reference Documentation

For further reference, please consider the following sections:

* [Official Gradle documentation](https://docs.gradle.org)
* [Spring Boot Gradle Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.2.0/gradle-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.2.0/gradle-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/3.2.0/reference/htmlsingle/index.html#web)
* [Spring Data JPA](https://docs.spring.io/spring-boot/docs/3.2.0/reference/htmlsingle/index.html#data.sql.jpa-and-spring-data)
* [Flyway Migration](https://docs.spring.io/spring-boot/docs/3.2.0/reference/htmlsingle/index.html#howto.data-initialization.migration-tool.flyway)

### Guides

The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)
* [Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)

### Additional Links

These additional references should also help you:

* [Gradle Build Scans – insights for your project's build](https://scans.gradle.com#gradle)

