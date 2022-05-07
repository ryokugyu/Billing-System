# Billing System 
 The aim of this project is to create Vegetable Billing System using Java Spring Boot and Angular. Here, we have a predefined list of vegetables and the prices. Customer can login or register into the application and and add the items as per there requirements. User can select the items to add and the quantity. After the submits the item list, a bill will get genreated. For Authorization, JWT( JSON Web Based Token) will be used.

# Technical Stack
**Backend Technologies** - Java 8, Spring Boot, Spring MVC, Spring Data JPA
**Frontend Tehnologies** - HTML5, CSS3, Bootstrap 4, Angular 8
**Database** - In Memory Database - *H2*
**Unit Testing** - JUnit, Mockito
**Other Technologies** - REST API, Eureka Discovery Server, Swagger UI, Spring Cloud Config, Spring Security

# The application has following services:
1. Eureka Service - Discovery Server for all the microservices
2. Config Service - Centralized Configuration Management
3. Authorization Service - For user authorization using JWT Tokens and new user registration
4. Vegetable Detail Service - Connected with the database and contains information for the vegetable list and prices
5. Process Bill Service - Based on the user input, final bill will get generated
6. Billing System Portal - Front end portal in *Angular*
