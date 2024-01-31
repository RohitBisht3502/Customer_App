# <h1 align = "center"> Customer Management CRUD Application </h1>
___ 
<p align="center">
<a href="Java url">
    <img alt="Java" src="https://img.shields.io/badge/Java->=8-darkblue.svg" />
</a>
<a href="Maven url" >
    <img alt="Maven" src="https://img.shields.io/badge/maven-4.0-brightgreen.svg" />
</a>
<a href="Spring Boot url" >
    <img alt="Spring Boot" src="https://img.shields.io/badge/Spring Boot-3.1.3-brightgreen.svg" />
</a>
    <img alt = "License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
    </a>
</p>


---

<p align="left">

## Overview

This project is a CRUD (Create, Read, Update, Delete) application for managing customer data. It provides a backend API built with Spring Boot, uses MySQL as the database, and incorporates JWT (JSON Web Token) authentication for secure user interactions.

## Technologies Used

- **Framework:** Spring Boot
- **Language:** Java
- **Build Tool:** Maven
- **Database:** MySql
- **Authentication:** JWT (JSON Web Token)
---
### Model
1. **Customer:**
2. **Admin:**
3. **JwtRequest:**
4. **JwtResponse:**
 ->This Patient Token is only for when a patient book an appointment so they will get token in their register email.

### Key Features

1. **Create a Customer**
The application allows users to create new customer profiles by providing essential information such as first name, last name, address details, email, and phone number.

2. **Update a Customer**
Users can update existing customer records, modifying details like the customer's address, email, or phone number.

3. **Get a List of Customers**
The application provides a paginated and sortable list of customers, enabling users to efficiently browse and manage a large volume of customer data. The search functionality allows users to find specific customers based on various criteria.

4. **Get a Single Customer by ID**
Users can retrieve detailed information about a specific customer by providing the unique identifier (ID) associated with that customer.

5. **Delete a Customer**
The application supports the deletion of customer records, ensuring the removal of outdated or irrelevant information.

6. **Authentication with JWT Security**
To enhance security, the application implements JSON Web Token (JWT) authentication. Users must authenticate themselves using valid credentials, and subsequent requests to secured endpoints require the inclusion of a valid JWT token in the Authorization header.
   ```
### Services
The Services layer implements the core business logic, data processing, and interaction with the data repository. Key responsibilities include:

- Validating input data.
- Performing CRUD operations on restaurant data.
- Handling data transformations and interactions with external systems (if applicable).
  
1. **User Service:**
2. **JWT Service:**
3. **Customer Service:**
4. **CustomUserDetailService:**

### Repository

The Repository layer manages data access to the underlying database. It handles database operations such as Create, Read, Update, and Delete (CRUD) for patient,doctor and token data etc. Additionally, it may include data mapping and conversion between Java objects and database entities.

## Database
- MySql database is used


### Customer Class

The Customer class has the following attributes:

- `customerId` (Type: Long): A unique identifier for each customer.
- `firstName` (Type: String): The first name of the customer.
- `lastName` (Type: String): The last name of the customer.
- `street` (Type: String): The street information associated with the customer's address.
- `address` (Type: String): The detailed address information of the customer.
- `city` (Type: String): The city where the customer resides.
- `state` (Type: String): The state or region where the customer is located.
- `email` (Type: String): The email address of the customer.
- `phone` (Type: String): The contact phone number of the customer.

## Project Summary

The Customer Management CRUD Application is a comprehensive solution for efficiently managing customer data through Create, Read, Update, and Delete (CRUD) operations. This application utilizes a robust backend built with Spring Boot, employs MySQL as the database for data storage, and implements JSON Web Token (JWT) security to ensure secure user interactions.

Key Features:

- Data validation to ensure data integrity.
- Clean code separation with a layered architecture (Controller, Services, Repository).
- Robust error handling for improved reliability.
- Java-based backend and Maven for build management.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

Thank you to the Spring Boot and Java communities for providing excellent tools and resources.

## Contact
For questions or feedback, please contact [Rohit singh bisht](mailto:business.rohitbisht3502@gmail.com)
