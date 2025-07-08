# Distributed Transaction Tracker

A Java Spring Boot application designed to track distributed transactions across multiple microservices with high scalability and reliability.

## Features
- Multi-tier REST API for managing and querying transactions
- Built with Spring Boot, leveraging Spring Data JPA and an in-memory H2 database for quick setup
- Designed for scalability, fault tolerance, and ease of maintenance
- Includes clean separation of concerns with controller, service, and repository layers
- Follows best practices in object-oriented design and coding standards
- Comprehensive unit testing for core components

## Technologies Used
- Java 17
- Spring Boot
- Spring Data JPA
- H2 In-Memory Database
- Maven
- RESTful API design principles

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/tolujoseph/distributed-transaction-tracker.git
   cd distributed-transaction-tracker

2. Build and run the application:
    ./mvnw spring-boot:run
Or with Maven installed:

    mvn spring-boot:run
3. Access the API at http://localhost:8080/api/transactions