# <h1 align = "center">  Expense Tracker API with Deployment on AWS using Ci-Cd Pipeline   </h1>
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
## Overview 🪟
<p align="center">This project, named " Expense Tracker API," is a robust Spring Boot application designed for managing user products efficiently with authentication. It provides a set of API endpoints that allow user to signup which store password in db will be encrypted format,signin with mail integration using tokens, and then user can perform crud operation on products,This application will use MySQL db for storin information and this is deployed on AWS machine for public using Ci-Cd pipeline with proper authentication. 
</p>

<!-- Table of Contents -->
## Table of Contents📑
1. [Technologies Used](#technologies-used)
2. [Key Features](#key-features)
3. [Usage](#usage)
4. [API reference](#api-reference)
5. [License](#license)
6. [Acknowledgments](#acknowledgments)
7. [Contact](#contact)

<!-- Technologies Used -->
## Technologies Used🧑‍💻
- Java 17
- Spring Boot
- Spring Web Initializer
- Maven
- Spring Web Dependency
- MySQL
- AWS Server
- Github

<!-- Model --->

## Models Key Features🔑
### 1 -> User Model
    Attribute's
        private Integer userId;
        private String UserName;
        private Gender gender;
        private String email;
        private String password;
        private String phoneNumber;
 

### 2 -> Product Model
    Attributes's
          private  Integer prodID;
          private String title;
          private String description;
          private  Double price;
          private LocalDate date;
          private LocalDateTime Time;

          <!-- Usage -->
## Usage
- Access the application at `http://localhost:8080`.
- Use the provided API endpoints to manage your User Management.

### Controller🎮:
- It consists of a class named APIController which basically controls the flow of data.
- @RestController annotation is used to make the APIController as a controller layer.
- We perform the CRUD operations such as @PostMapping , @GetMapping , @PutMapping , @DeleteMapping.



 <!-- Acknowledgments -->
## Acknowledgments
- Thank you to the Spring Boot and Java communities for providing excellent tools and resources.

<!-- Contact -->
## Contact📲
For questions or feedback, please contact : Avadhesh Shukla👍
- Maild Id 📧: avadheshsukla1636@gmail.com

<h1 align="center">Thank You💖...<h1>
<h3 align = "center"> ***********************************************************<h3>




 
