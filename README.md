# CivicConnect – Spring Boot Citizen Feedback Management System

![Java](https://img.shields.io/badge/Java-21-orange)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen)
![Maven](https://img.shields.io/badge/Build-Maven-blue)
![Security](https://img.shields.io/badge/Security-Spring%20Security-red)

CivicConnect is a **secure, scalable, and role-based web application** built using **Spring Boot MVC** to streamline citizen feedback and complaint management.  
This repository combines **the complete Spring Boot implementation and the academic project report** into a single, professional GitHub project.

---

## 📘 Project Overview

Municipal administrations often face challenges in efficiently collecting, tracking, and resolving citizen complaints. Traditional systems such as complaint registers, helplines, and emails lack transparency, real-time tracking, and accountability.

**CivicConnect** solves this problem by providing a **centralized digital platform** where:
- Citizens can submit civic issues
- Track resolution status in real time
- Provide feedback and reactions
- Administrators can securely manage and resolve complaints

The application follows **enterprise-grade design principles** using Spring Boot, Spring Security, and JPA.

---

## 🎯 Project Objectives

- Centralize citizen feedback and complaints
- Enable real-time complaint tracking
- Enforce role-based access control
- Improve transparency and accountability
- Support Smart City and E-Governance initiatives

---

## 🏗️ System Architecture (MVC)

CivicConnect follows a **4-layer Spring Boot MVC architecture**:

- **View Layer** – Thymeleaf templates for UI rendering  
- **Controller Layer** – Handles HTTP requests and routing  
- **Service Layer** – Contains business logic and validations  
- **Repository Layer** – Manages database operations via JPA  

This layered approach ensures **scalability, maintainability, and security**.

---

## 📂 Repository Structure

```text
CivicConnect-SpringBoot/
│
├── src/
│   ├── main/java/
│   │   ├── controller        # MVC Controllers
│   │   ├── service           # Business logic
│   │   ├── repository        # JPA repositories
│   │   ├── entity            # Database entities
│   │   └── security          # Spring Security configuration
│   │
│   ├── main/resources/
│   │   ├── templates         # Thymeleaf templates
│   │   └── application.properties
│   │
│   └── test/java/            # JUnit & functional tests
│
├── database/
│   └── posts-data.sql        # Sample database data
│
├── docs/
│   └── CivicConnect_Project_Report.pdf   # Academic project report
│
├── pom.xml                   # Maven configuration
├── mvnw / mvnw.cmd           # Maven wrapper
└── README.md                 # Project documentation

```
---
🚀 Functional Features

✅ User Authentication
Secure user registration and login

Session-based authentication

✅ Role-Based Access Control
Citizen and Admin roles

Restricted admin-only operations

✅ Complaint & Post Management
Create civic issues / posts

View and track complaint status

✅ Feedback & Reactions
Like / Neutral / Dislike reactions

Community engagement tracking

✅ User Profile
Activity history and participation summary

✅ Error Handling
Custom 404 page

Access-denied handling
---

##🔐 Security Features
Spring Security integration

BCrypt password encryption

Role-based authorization

Protected endpoints and routes

Secure session management

Prevention of unauthorized access
---
##🧪 Testing
The application includes JUnit and functional testing to ensure reliability and correctness:

Authentication and authorization testing

Role-based access validation

Post creation and retrieval testing

Application context loading tests
---

##📂 Test location:

text
Copy code
src/test/java/
---

##🛠️ Technology Stack
Backend
Java 21

Spring Boot 3.x

Spring Security

Spring Data JPA

Hibernate

Frontend
Thymeleaf

HTML5

CSS3

Bootstrap

Database
MySQL

H2 (for testing)

Tools & Build
Maven

JUnit

Visual Studio Code
---

##⚙️ Setup & Execution
1️⃣ Clone the Repository
bash
Copy code
git clone https://github.com/your-username/CivicConnect-SpringBoot.git
cd CivicConnect-SpringBoot
2️⃣ Configure Database
Update application.properties:

properties
Copy code
spring.datasource.url=jdbc:mysql://localhost:3306/civicconnect
spring.datasource.username=root
spring.datasource.password=yourpassword
3️⃣ Run the Application
bash
Copy code
./mvnw spring-boot:run
4️⃣ Access the Application
text
Copy code
http://localhost:8080
---
##📈 Performance Highlights
⏱ Average response time: < 2 seconds

👥 Supports 50+ concurrent users
---

##📊 Optimized JPA queries

🔒 Secure authentication and authorization

🖥️ Responsive UI with Thymeleaf templates
---

##👩‍💻 Authors
Gayathri Devi C (22MIS0452)
---

##✅ Conclusion
CivicConnect demonstrates real-world Spring Boot application development with a strong focus on security, modular architecture, testing, and scalability.
By combining source code, security implementation, testing, and academic documentation in one repository, this project presents a complete, production-style solution
