# Exploring the Testing Hyperpyramid (Maven Version)
Code repo for the talk by @daviddenton and @s4nchez

This is a Maven-based version of the original Gradle project from https://github.com/http4k/exploring-the-testing-hyperpyramid

- [video](https://bit.ly/hyperpyramid-kotlinconf)
- [slides](https://speakerdeck.com/daviddenton/exploring-the-testing-hyperpyramid-with-kotlin-and-http4k)

## Building the Project

This is a Maven multi-module project. To build it:

```bash
mvn clean install
```

To run tests:

```bash
mvn test
```

## Modules

- **infra**: Core infrastructure and utilities
- **warehouse**: Warehouse service with database support
- **shop**: Shop service with email notifications
- **api-gateway**: API Gateway with OAuth security
- **images**: Image server
- **e2e**: End-to-end tests

## Requirements

- Java 21
- Maven 3.6+
