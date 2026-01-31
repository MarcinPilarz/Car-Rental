# Car Rental System – Web Application

This repository contains a **team project** developed as part of university coursework.  
The application is a web-based **car rental management system** implemented using **Spring Boot** for the back-end and **React** for the front-end.

Due to the educational nature of the project and the learning process involving different programming languages and conventions, naming within the codebase may be inconsistent (e.g. mixed Polish and English identifiers such as `czytajSamochod` and `addCar`).

---

## Project Description

The goal of the project was to design and implement a full-stack web application that supports the car rental process, including user authentication, role-based access, vehicle management, and reservation handling.

The system is divided into a front-end client application and a RESTful back-end service connected to a relational database.

---

## Main Features

### Authentication and Authorization
- user registration and login,
- JWT-based authentication,
- role-based access control (e.g. USER, ADMIN),
- access token implemented,
- refresh token implemented (currently not fully functional).

### User Functionality
- browsing available cars,
- viewing car details,
- creating car rental reservations,
- managing own reservations.

### Admin Functionality
- managing vehicles (add, edit, delete),
- managing users,
- managing reservations,
- administrative access to protected endpoints.

---

## Technologies Used

### Front-end
- React
- React Router
- Axios
- JWT handling

### Back-end
- Java
- Spring Boot
- Spring Security
- REST API
- JWT authentication

### Database
- SQL database (e.g. MySQL)

---

## System Architecture

- Front-end communicates with the back-end via REST API
- Authentication based on JWT tokens
- Role-based authorization handled by Spring Security
- Data persistence handled through a relational database

---

## Running the Application

### Back-end (Spring Boot)

1. Open the back-end project in an IDE (e.g. IntelliJ IDEA or Eclipse)
2. Configure database connection in:
   ```properties
   application.properties
   spring.datasource.url=...
   spring.datasource.username=...
   spring.datasource.password=...
