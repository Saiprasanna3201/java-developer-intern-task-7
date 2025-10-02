# Employee Database App (Java JDBC)

## 📌 Project Overview
This project demonstrates **Java JDBC connectivity** with a MySQL database by building an **Employee Management System**.  
It supports **CRUD operations** (Create, Read, Update, Delete) on employee records using a console-based interface.  
The project showcases the use of **JDBC, PreparedStatement, SQL queries, and database connectivity** in Java.

---

## 🚀 Features
- ✅ Connect Java application to MySQL using JDBC  
- ✅ Add new employees with name, role, and salary  
- ✅ View all employee records from the database  
- ✅ Update employee role and salary by ID  
- ✅ Delete employee records by ID  
- ✅ Prevents SQL Injection using **PreparedStatement**

---

## 🛠️ Tech Stack
- **Java** (JDK 8 or later)  
- **MySQL** (or PostgreSQL with minor changes)  
- **JDBC Driver** (Connector/J for MySQL)  
- **IDE**: VS Code / IntelliJ / Eclipse  

---

## ⚙️ Setup Instructions
### 1. Database Setup
Run the following SQL commands in MySQL:
```sql
CREATE DATABASE employeeDB;
USE employeeDB;

CREATE TABLE employees (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100) NOT NULL,
    role VARCHAR(100) NOT NULL,
    salary DOUBLE
);
