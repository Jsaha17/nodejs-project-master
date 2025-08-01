# 🔐 Node.js JWT Authentication API

This project implements a secure **user authentication and role-based access control system** using **Node.js**, **Express.js**, **JWT**, **MySQL**, and **Sequelize ORM**. It’s ideal for SaaS platforms and admin dashboards requiring protected APIs.

> ✅ Developed as part of my backend engineering learning, showcasing scalable auth system design using JSON Web Tokens and database-driven roles.

---

## 📦 Tech Stack

- **Backend:** Node.js, Express.js  
- **Database:** MySQL, Sequelize ORM  
- **Security:** JWT (access & refresh tokens), Bcrypt  
- **Others:** CORS, dotenv

---

## ✨ Features

- User Registration and Login
- Hashed passwords using `bcryptjs`
- JWT Token Generation and Validation
- Role-based Access Control: `user`, `moderator`, `admin`
- Protected Routes Example
- Sequelize ORM Integration with MySQL

---

## 🧠 Authentication Flow

![Auth Flow](./jwt-token-authentication-node-js-example-flow.png)
![Refresh Flow](./jwt-refresh-token-node-js-example-flow.png)

---

## 🛠️ Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Jsaha17/nodejs-jwt-auth-master.git
cd nodejs-jwt-auth-master
### 2. Install Dependencies
npm install
### 3. Set Up Environment Variables
Create a .env file and add:
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=jwt_auth_db
JWT_SECRET=your_jwt_secret
### 4. Start Server
node server.js
