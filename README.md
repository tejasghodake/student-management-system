# 🎓 Student Management System

A full-stack Spring Boot application for managing student records using Java, Spring Boot, Thymeleaf, and MySQL.

---

## 🚀 Features

- ✅ Add, Edit, Delete, and View student records
- ✅ MVC Architecture (Controller → Service → Repository)
- ✅ Dynamic HTML UI using Thymeleaf
- ✅ Database integration using Spring Data JPA + MySQL
- ✅ Clean code structure with layered separation

---

## 🔧 Tech Stack

- Java 17+
- Spring Boot
- Spring Data JPA
- Thymeleaf
- MySQL
- Maven

---

## 📂 Project Structure

src/
├── main/
│   ├── java/
│   │   └── com.tejas.student
│   │       ├── controller
│   │       ├── model
│   │       ├── repository
│   │       └── service
│   └── resources/
│       ├── templates/
│       └── application.properties

---

## ⚙️ Setup Instructions

### ✅ Step 1: Create MySQL Database

Open MySQL and run:

CREATE DATABASE student_db;

### ✅ Step 2: Update application.properties

spring.datasource.url=jdbc:mysql://localhost:3306/student_db  
spring.datasource.username=root  
spring.datasource.password=yourpassword

spring.jpa.hibernate.ddl-auto=update  
spring.jpa.show-sql=true  
spring.thymeleaf.cache=false

### ✅ Step 3: Run the Project

Use your terminal or IDE and run:

mvn spring-boot:run

Then open your browser:

http://localhost:8080

---

## 📌 Author

**Tejas Ghodake**  
Java Backend Developer | Spring Boot | MySQL | Thymeleaf  
GitHub: https://github.com/tejasghodake  
LinkedIn: https://www.linkedin.com/in/tejasghodake/

---

## 🏷️ Tags

#Java #SpringBoot #MySQL #Thymeleaf #BackendDevelopment #StudentManagement
