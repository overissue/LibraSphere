# LibraSphere

LibraSphere is an Online Library System crafted to cultivate proficiency in modern Java development technologies. This project employs a microservices architecture, leveraging Spring Boot, Docker, and an array of other tools and frameworks. LibraSphere serves as a practical platform for developers to immerse themselves in a diverse technological ecosystem within a real-world context.

## Overview

- **Backend**: Java/Spring
- **Frontend**: React

## Features

- **User Registration and Authentication**: Seamlessly manage user accounts and ensure secure access.
- **Book Management**: Effortlessly handle book operations including addition, editing, deletion, and searching.
- **Review and Rating System**: Foster user engagement by enabling book reviews and ratings.
- **RESTful APIs**: Facilitate seamless interaction between microservices.
- **Containerization with Docker**: Streamline deployment and scalability with Docker containers.
- **Comprehensive Testing**: Ensure robustness with JUnit and Mockito for thorough unit and integration testing.
- **Security**: Safeguard your application with Spring Security.

## Technologies Used

- **Microservices Architecture**: Decoupled services for user management, book management, and reviews.
- **Spring Boot**: Empowering the development of standalone, production-grade Spring-based applications.
- **JPA/Hibernate**: Facilitating Object-Relational Mapping (ORM) and database interactions.
- **Docker**: Simplifying application deployment through containerization.
- **Spring Security**: Ensuring application security through authentication and authorization.
- **RESTful Web Services**: Enabling seamless communication between microservices.
- **GIT/GitHub**: Managing version control and facilitating collaboration.
- **MS SQL**: Managing relational databases efficiently.
- **Testing**: Employing JUnit and Mockito for meticulous unit and integration tests.

application.properties:
spring.application.name=LibraSphere
spring.datasource.url=jdbc:sqlserver://localhost:1433;databaseName=libra
spring.datasource.username=username
spring.datasource.password=password
spring.datasource.driver-class-name=com.microsoft.sqlserver.jdbc.SQLServerDriver