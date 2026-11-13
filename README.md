<div align="center">

# 🌈 Angular 17 + Spring Boot CRUD App

### A colorful, full-stack CRUD demo powered by Angular, Spring Boot, and MySQL

<br />

![Angular](https://img.shields.io/badge/Angular-17-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Java](https://img.shields.io/badge/Java-17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

<br />

**A learning project demonstrating end-to-end CRUD application development.**

</div>

---

## ✨ About

This repository brings together an **Angular 17 frontend**, a **Spring Boot backend**, and **MySQL persistence** in a simple full-stack CRUD application. It’s a hands-on example of how a browser-based frontend can work with a Java backend and relational database.

## 🧰 Technology Stack

| Area | Technology |
| --- | --- |
| 🎨 Frontend | Angular 17, TypeScript |
| ⚙️ Backend | Spring Boot, Java 17 |
| 🗄️ Database | MySQL |

## 📁 Project Layout

```text
Angular-17-Spring-Boot-CRUD-Full-Stack-App/
├── Front End Project/                 # Angular application
├── YT-Springboot-Angular-Backend.zip  # Backend project archive
└── README.md
```

## ✅ Prerequisites

Install these before getting started:

- [Node.js](https://nodejs.org/) and npm
- [JDK 17 or newer](https://adoptium.net/)
- [MySQL Server](https://dev.mysql.com/downloads/)

## 🚀 Getting Started

### 1. Get the code

```bash
git clone https://github.com/Rawkesh2k/Angular-17-Spring-Boot-CRUD-Full-Stack-App.git
cd Angular-17-Spring-Boot-CRUD-Full-Stack-App
```

### 2. Start the Angular frontend

```bash
cd "Front End Project"
npm install
npm start
```

Open the local address reported by the Angular development server (commonly `http://localhost:4200/`).

### 3. Prepare and run the backend

Extract `YT-Springboot-Angular-Backend.zip` if necessary, then configure the Spring Boot datasource with your local MySQL database settings. From the backend project directory, run:

```bash
./mvnw spring-boot:run
```

> **Windows:** use `mvnw.cmd spring-boot:run` if the project includes the Maven wrapper for Windows.

## 🔐 Configuration & Security

- Configure the backend datasource for your own MySQL environment.
- Keep database credentials and other secrets out of source control.
- Check the backend project’s configuration and setup instructions for any additional database requirements.

## 🎓 Project Purpose

This is a learning/demo project focused on CRUD operations and full-stack integration. Explore the frontend and backend projects to follow how the application is put together.

## 📄 License

No explicit license is identified in this repository. Please contact the repository owner before reusing or redistributing the project.

---

<div align="center">

💖 **Built for learning full-stack development** · ⭐ Star the repo if you find it useful!

</div>
