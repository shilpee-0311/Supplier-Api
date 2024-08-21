# Supplier-Api
This project is a RESTful API built using Spring Boot to manage supplier details. The API allows users to query suppliers based on their location, nature of business, and manufacturing processes. It also supports pagination and includes proper input validation and exception handling.

Features
Retrieve supplier details by filtering on location, nature of business, and manufacturing processes.
Supports pagination for large data sets.
Input validation and basic exception handling.
Extensible for additional features like security, unit 

Key Directories:
controller: Handles incoming HTTP requests and returns the response.
service: Contains the business logic for supplier operations.
repository: Interface for database operations, powered by Spring Data JPA.
model: Entity classes representing the data model.
exception: Contains custom exception handlers for validation and error management.

Getting Started
Prerequisites
To run this project, you will need the following:

Java 8 or higher
Maven for dependency management
Spring Boot 
Database (MySQL) – Configuration can be set in application.properties

