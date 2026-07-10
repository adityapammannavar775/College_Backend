# College Management API

A robust RESTful API built with **Node.js**, **Express**, and **Mongoose** for managing a college database system. This project includes secure user authentication using **JWT (JSON Web Tokens)** and full **CRUD (Create, Read, Update, Delete)** operations for managing student records.

---

## 🚀 Features

* **User Authentication**: Secure user registration and login endpoints utilizing `bcryptjs` for password hashing and `jsonwebtoken` for stateless authentication.
* **Student Management**: Complete CRUD operations for handling student profiles.
* **Database Integration**: Structured data management using MongoDB and Mongoose schemas (User, Course, Teacher, Student).
* **Environment Configuration**: Protected environment variables handled via `dotenv`.

---

## 🛠️ Tech Stack

* **Backend**: Node.js, Express.js
* **Database**: MongoDB, Mongoose ODM
* **Security**: bcryptjs, JSON Web Tokens (JWT)
* **Configuration**: dotenv

---

## 📋 Prerequisites

Before running this project, ensure you have the following installed:
* [Node.js](https://nodejs.org/) (v14+ recommended)
* [MongoDB](https://www.mongodb.com/) (Running locally on `mongodb://127.0.0.1:27017`)

---

   ## ⚙️ Getting Started

### 1. Clone the Repository
```bash
git clone <repository-url>
cd <project-directory>
