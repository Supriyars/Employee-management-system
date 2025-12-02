Employee Management System — Full Stack Project

A full-stack Employee Management System built with React (frontend), Spring Boot (backend), and MySQL (database).
This project supports creating, updating, deleting, and listing employees and departments.

🚀 Tech Stack
Frontend

React

Axios

Bootstrap

React Router

Backend

Spring Boot

Spring Web

Spring Data JPA

MySQL Driver

Lombok (optional)

Database

MySQL

📁 Project Structure
employee-management-system/
   backend/       → Spring Boot API
   frontend/      → React UI
   README.md

⚙️ Backend Setup (Spring Boot)
1️⃣ Configure MySQL

Create a database:

CREATE DATABASE employee_management;

2️⃣ Update application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/employee_management
spring.datasource.username=mysql_username
spring.datasource.password=mysql_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

3️⃣ Run the backend

You can start it from IntelliJ or run:

mvn spring-boot:run


Backend runs on:

http://localhost:8081

💻 Frontend Setup (React)
1️⃣ Install dependencies
cd frontend
npm install

2️⃣ Start the React app
npm start


Frontend runs on:

http://localhost:3000

🔗 API Endpoints
Department APIs
GET    /api/departments
GET    /api/departments/{id}
POST   /api/departments
PUT    /api/departments/{id}
DELETE /api/departments/{id}

Employee APIs
GET    /api/employees
GET    /api/employees/{id}
POST   /api/employees
PUT    /api/employees/{id}
DELETE /api/employees/{id}

✨ Features
Backend

CRUD for Employees

CRUD for Departments

MySQL persistence

RESTful API using Spring Boot

Frontend

Add/Update/Delete employees

Select department from dropdown

Form validation

Responsive UI using Bootstrap

🛠️ How to Run the Full Project

Start MySQL server

Start backend (port 8081)

Start frontend (port 3000)

Open browser → http://localhost:3000

📌 Future Improvements

Authentication (JWT)

Pagination

Search filtering

User roles (Admin/User)
