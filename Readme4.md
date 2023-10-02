# <h1 align = "center"> Employee Address </h1>
___ 
<p align="center">
<a href="Java url">
    <img alt="Java" src="https://img.shields.io/badge/Java->=8-darkblue.svg" />
</a>
<a href="Maven url" >
    <img alt="Maven" src="https://img.shields.io/badge/maven-3.1.3-brightgreen.svg" />
</a>
<a href="Spring Boot url" >
    <img alt="Spring Boot" src="https://img.shields.io/badge/Spring Boot-3.0.6-brightgreen.svg" />
</a>
</p>

---

<p align="left">

<!-- Project Description -->
## Overview
<p align="center">This project,  Employee address," is a robust Spring Boot application designed for managing user data efficiently. It provides a set of API endpoints that allow you to perform various operations on user records, such as adding, retrieving, updating, and deleting user information. 
</p>

<!-- Table of Contents -->
## Table of Contents
1. [Technologies Used](#technologies-used)
2. [Key Features](#key-features)
3. [Usage](#usage)
4. [API reference](#api-reference)
5. [License](#license)
6. [Acknowledgments](#acknowledgments)
7. [Contact](#contact)

<!-- Technologies Used -->
## Technologies Used
- Java 8
- Spring Boot
- Spring Web Initializer
- Maven
- Spring Web Dependency
- SQL DRIVER
- JPA
- SWAGGER
- sQL DATABASE
- OneToOne Mapping

## Model Classes
- Address Entity :-lass, which is typically used to represent address information. The class includes fields for various address components and is designed for use with JPA (Java Persistence API) in a database-driven application.
- Employee Entity :-class, which is typically used to represent employee information. The class includes fields for employee details, such as first name, last name, and an associated address. Additionally, it is designed for use with JPA (Java Persistence API) in a database-driven application.
## Controller Class
- AddressController :-The AddressController is a Spring MVC controller class responsible for handling HTTP requests related to address operations in your Spring Boot application.
- Employee Controller :-class in the com.geekster.Employee.address.Controller package. This controller class handles HTTP requests related to employee data in an address management system.
## Service Class
- AddressService :-The AddressService is a service class in your Spring Boot application responsible for handling address-related operations. It includes the addAllAddress method, which allows you to add multiple addresses to your system.
- Employee Service :-class, which is a service class responsible for handling employee-related operations in the context of your application.
## Repo Class
- Address Repository :-interface, which is likely a repository interface for handling address-related data using Spring Data JPA.
- Employee Repository Interface :-interface, which serves as a repository for managing Employee entities. The interface extends JpaRepository, indicating its usage in Spring Data JPA for performing database operations on Employee objects.


<!-- Key Features -->
## Key Features
- Get User by Id.
- Get all User.
- Get User Details By Id.
- Delete Product By Id.
- Update UserName

<!-- Usage -->
## Usage
- Access the application at `http://localhost:8080`.
- Use the provided API endpoints to CRUD Operation And Custom finder.

### Controller:
- It consists of a class named APIController which basically controls the flow of data.
- @RestController annotation is used to make the APIController as a controller layer.
- We perform the CRUD operations such as @PostMapping , @GetMapping , @PutMapping , @DeleteMapping.

### API Reference

#### Add Users :
PostMethod :  http://localhost:8080/posts
### UPdate User:
PutMapping : http://localhost:8080/companyName/Id

### Delete User:
DeleteMapping: http://localhost:8080/Delete/Id/


#### Get All Users :
 - GET Method : http://localhost:8080/get

 

 <!-- Acknowledgments -->
## Acknowledgments
- Thank you to the Spring Boot and Java communities for providing excellent tools and resources.

<!-- Contact -->
## Contact
For questions or feedback, please contact : SHRAVAN KUMAR   -
- Maild Id : shravankm93@gmail.com

<h1 align="center">Thank You...<h1>
<h3 align = "center"> ***********************************************************<h3>
*  Employee Address
