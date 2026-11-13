# Angular 17 + Spring Boot CRUD Full-Stack App

A full-stack CRUD application combining an Angular 17 frontend with a Spring Boot backend and MySQL persistence. This repository includes a frontend project folder and a backend archive for the Java service.

## Stack

- Angular 17
- TypeScript
- Spring Boot
- Java 17
- MySQL

## Project Structure

```text
Angular-17-Spring-Boot-CRUD-Full-Stack-App/
├── Front End Project/
├── YT-Springboot-Angular-Backend.zip
├── README.md
└── project files
```

## Prerequisites

- Node.js + npm
- JDK 17+
- MySQL server

## Getting Started

```bash
git clone https://github.com/Rawkesh2k/Angular-17-Spring-Boot-CRUD-Full-Stack-App.git
cd Angular-17-Spring-Boot-CRUD-Full-Stack-App
```

### Frontend

```bash
cd "Front End Project"
npm install
npm start
```

### Backend

Extract the backend archive if needed and configure the datasource in the Spring Boot application before running it.

```bash
./mvnw spring-boot:run
```

## Configuration

Use environment-specific database credentials and avoid committing secrets to version control.

## Notes

This project is a learning/demo full-stack app focused on CRUD operations and full-stack integration.

## License

No explicit license was identified. Check with the repository owner before reuse or redistribution.
