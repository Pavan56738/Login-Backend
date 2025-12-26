# 🔐 Login & Registration System  
Spring Boot Backend + HTML/CSS/JS Frontend

## 📌 Project Overview
This project is a Login and Registration system built using Spring Boot for backend and HTML, CSS, JavaScript for frontend.  
It allows users to register and login with data stored in MySQL.

## 🧱 Architecture
Frontend → REST API → Service → Repository → MySQL

## 🛠️ Tech Stack
Backend:
- Java 17
- Spring Boot
- Spring Data JPA
- MySQL
- Maven

Frontend:
- HTML
- CSS
- JavaScript (Fetch API)

## 📂 Project Structure
backend/
 ├── src/main/java/com/example/demo
 │    ├── controller
 │    ├── dto
 │    ├── entity
 │    ├── repository
 │    └── DemoApplication.java
 │
 └── src/main/resources
      ├── static
      │    ├── Animationlogin.html
      │    ├── register.html
      │    └── style.css
      └── application.properties

## 🗄️ Database Setup
CREATE DATABASE springboot_db;

application.properties:
spring.datasource.url=jdbc:mysql://localhost:3306/springboot_db
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update

## 🔐 APIs
POST /api/users/register  
POST /api/users/login

## ▶️ Run Project
cd backend  
mvn clean  
mvn spring-boot:run  

## 🌐 URLs
http://localhost:8080/Animationlogin.html  
http://localhost:8080/register.html  

## 🚀 Future Scope
- JWT Authentication
- Password Encryption
- Dashboard

## 👨‍💻 Developer
Pavan Kalyan  
BTech CSE
