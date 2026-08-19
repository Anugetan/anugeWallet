# 💰 Anuge Wallet Backend

A **digital wallet backend** built with **Java and Spring Boot**. It provides REST APIs for user authentication, wallet management, deposits, withdrawals, payment methods, and transaction records.

## 🚀 Features

* User registration and login
* User authentication and logout
* Wallet balance management
* Deposit and withdrawal transactions
* Payment method management
* Transaction history
* Current user information
* REST API integration
* Relational database integration

## 🛠️ Tech Stack

* **Java**
* **Spring Boot**
* **Spring Security**
* **Spring Data JPA / Hibernate**
* **MariaDB / MySQL / PostgreSQL**
* **Maven**
* **Angular / TypeScript**
* **Postman**
* **Git & GitHub**

## 🏗️ Architecture

```text
Angular Frontend
       ↓
REST Controller
       ↓
Service Layer
       ↓
Repository
       ↓
JPA Entity
       ↓
Relational Database
```

## 📁 Project Structure

```text
src/main/java/com/anuge/wallet/

├── config/
├── controller/
├── dto/
├── entity/
├── repository/
└── service/
```

## 🔗 Main API

| Method | Endpoint                     | Description         |
| ------ | ---------------------------- | ------------------- |
| POST   | `/api/loginAuth/login`       | User login          |
| POST   | `/api/loginAuth/register`    | User registration   |
| POST   | `/api/loginAuth/logout`      | User logout         |
| GET    | `/api/loginAuth/me`          | Get current user    |
| POST   | `/api/transactions/deposit`  | Deposit funds       |
| POST   | `/api/transactions/withdraw` | Withdraw funds      |
| GET    | `/api/transactions`          | Transaction history |

## 🎯 Purpose

AnuGE Wallet is a full-stack digital wallet project demonstrating **Spring Boot backend development, REST APIs, authentication, database management, and Angular integration**.

## 👨‍💻 Developer

**Jonathan Eguna**
Computer Engineering Graduate | Full-Stack / Backend Developer
