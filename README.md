# Spring Boot Course Projects

This repository contains the projects and exercises I built while following a Spring Boot course on Udemy.

## Course

This work comes from the Udemy course:

- "Spring Boot 4, Spring 7 & Hibernate for Beginners"

Alternate/expanded listing used on the course page:

- "Spring Boot 4: Learn Spring 7, Spring Core, Spring REST, Spring Security, JPA, Hibernate, Swagger, Spring MVC, MySQL"

Instructor: Chad Darby

If you'd like, I can add a direct link to the Udemy course page — tell me the preferred URL and I'll insert it.

## About

The code in this repo is from a hands-on Spring Boot course I completed on Udemy. It includes example projects, exercises, and notes demonstrating Spring Boot fundamentals such as:

- Building RESTful APIs with Spring Boot
- Dependency injection and configuration
- Data persistence with Spring Data JPA
- Working with embedded databases (H2) and external databases
- Validation, exception handling, and logging
- Unit and integration testing

## Repository Structure

Each project or exercise is kept in its own module/directory. Typical folders you may find:

- `src/` - Java source code and resources
- `pom.xml` or `build.gradle` - build configuration (Maven or Gradle)
- `README.md` (per-project) - project-specific notes (if present)

## Prerequisites

- JDK 17 (or the version used in the course)
- Maven 3.6+ or Gradle (depending on the project build files)
- An IDE such as IntelliJ IDEA or VS Code (optional)

## How to build and run

Using Maven (example):

1. Build the project:

   mvn clean package

2. Run the application:

   mvn spring-boot:run

Or run the generated jar:

   java -jar target/<project-name>-0.0.1-SNAPSHOT.jar

Replace `<project-name>` with the module or artifact name.

## Running tests

To run unit and integration tests with Maven:

   mvn test

## Notes

- Some projects use an embedded H2 database by default for quick testing. Check `application.properties`/`application.yml` for configuration.
- If any project requires an external database, update the datasource configuration with your credentials.

## Credits

This repository contains work based on a Udemy course by Chad Darby (see the Course section above for the exact title used).

## Author

- faresmoustafa1

## License

This repository is provided for personal learning purposes. If you want, I can add an open-source license (e.g., MIT).