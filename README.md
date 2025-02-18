# Overview
This is a Talent tracker laboratory
## Required
- Java 23
- IDE
- Maven

## Technologies
- Java
- Exception management with @ControllerAdvice
- Spring Boot
- Spring security
- Spring Data
- Spring Batch
- Spring Actuators
- SQL
- Unit testing: JUnit 5 & Mockito
- E2E testing with Karate
- Swagger
- DevOps and deployment: Docker, GitHub actions

  ## Features
  - Bench plan. Module to create a 1 month plan.
  - Report plan. Here you could report your daily progress  of your trainings.
  - 

## Endpoints
 |Method|Endpoint| Description|
 |---|---|---|
 |GET|employees| Find all the employees with pagination|
 |GET|employees/{id}| Find employee by id|
 |POST|employees/{id}/skills| Add skills|
 |PATCH|employees/{id}/skills| Update skills|
 |POST|employees/{id}/certifications| Add skills|
 |POST|employees/registry| Register a new employee|
  
