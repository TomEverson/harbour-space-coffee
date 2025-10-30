# Read Me First
The following was discovered as part of building this project:

* The original package name 'space.harbour.kotlin.' is invalid and this project uses 'space.harbour.kotlin' instead.

# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Gradle documentation](https://docs.gradle.org)
* [Spring Boot Gradle Plugin Reference Guide](https://docs.spring.io/spring-boot/3.5.7/gradle-plugin)
* [Create an OCI image](https://docs.spring.io/spring-boot/3.5.7/gradle-plugin/packaging-oci-image.html)
* [Spring Web](https://docs.spring.io/spring-boot/3.5.7/reference/web/servlet.html)
* [Spring Data JPA](https://docs.spring.io/spring-boot/3.5.7/reference/data/sql.html#data.sql.jpa-and-spring-data)
* [Spring Data JDBC](https://docs.spring.io/spring-boot/3.5.7/reference/data/sql.html#data.sql.jdbc)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)
* [Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)
* [Using Spring Data JDBC](https://github.com/spring-projects/spring-data-examples/tree/master/jdbc/basics)

### Additional Links
These additional references should also help you:

* [Gradle Build Scans – insights for your project's build](https://scans.gradle.com#gradle)

### Kotlin Logging
Documentation for kotlin-logging framework used in this project:

* [kotlin-logging GitHub](https://github.com/oshai/kotlin-logging) - Main repository and documentation
* [Guide to Kotlin-Logging](https://www.baeldung.com/kotlin/kotlin-logging-library) - Comprehensive tutorial
* [Logback Configuration](https://logback.qos.ch/manual/configuration.html) - Logback configuration reference

The logging configuration can be found in `src/main/resources/logback-spring.xml`. You can adjust log levels and patterns there.

### Kotest Testing Framework
Documentation for Kotest testing framework used in this project:

* [Kotest Documentation](https://kotest.io/) - Main documentation
* [Getting Started with Kotest](https://kotest.io/docs/quickstart) - Quick start guide
* [Kotest Assertions](https://kotest.io/docs/assertions/assertions.html) - Assertion styles and matchers
* [Kotest Spring Extension](https://kotest.io/docs/extensions/spring.html) - Spring Boot integration
* [Testing Styles](https://kotest.io/docs/framework/testing-styles.html) - Different test styles (FunSpec, StringSpec, etc.)

### Continuous Integration
This project includes GitHub Actions for automated testing:

* [GitHub Actions Documentation](https://docs.github.com/en/actions) - Learn about GitHub Actions
* The CI workflow runs automatically on push and pull requests to `main` and `develop` branches
* Workflow file: `.github/workflows/ci.yml`

