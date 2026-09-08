# 👋 Hi, I'm Sushmitha Katika

### 🚀 Java Backend Developer | Spring Boot | Microservices | REST APIs

I'm a **Java Backend Developer** passionate about designing scalable backend systems, developing RESTful APIs, and building production-oriented applications using **Java, Spring Boot, and Microservices**.

I enjoy understanding how real-world software systems work — from **database design and authentication to asynchronous communication, caching, containerization, and API architecture**.

🎯 **Currently focused on:** Java Backend Development • Spring Boot • Microservices • System Design • DSA • React + TypeScript

---

## 🧑‍💻 About Me

* 🎓 B.Tech in **Information Technology** from **Anurag University**
* 📊 CGPA: **8.68 / 10**
* 💻 Focused on **Java Backend & Full Stack Development**
* 🔧 Hands-on experience building **Spring Boot REST APIs and Microservices**
* 🔐 Interested in **secure, scalable and maintainable backend systems**
* 🏗️ Currently building **BuildFlow — a Construction Management & Intelligence Platform**
* 🛒 Built a complete **E-commerce Microservices Platform**
* 🌱 Currently strengthening **Advanced Java, DSA, Microservices and System Design**
* 🤝 Open to opportunities as a **Java Backend Developer / Software Engineer / Full Stack Developer**

---

# 🛠️ Technical Skills

### 💻 Programming

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge\&logo=openjdk\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge\&logo=typescript\&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)

### 🚀 Backend Development

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge\&logo=springboot\&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge\&logo=springsecurity\&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge\&logo=hibernate\&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20APIs-02569B?style=for-the-badge)

* Spring Boot
* Spring MVC
* Spring Data JPA
* Hibernate / JPA
* Spring Security
* JWT Authentication
* RESTful API Development
* Exception Handling & Validation
* Layered Architecture
* Microservices Architecture

### 🧩 Microservices & Distributed Systems

![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge\&logo=apachekafka\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge\&logo=redis\&logoColor=white)

* Microservices Architecture
* API Gateway
* Service-to-Service Communication
* Apache Kafka
* Event-Driven Architecture
* Redis Caching
* Resilience & Fault Tolerance
* Distributed System Concepts

### 🗄️ Databases

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge\&logo=mongodb\&logoColor=white)

* MySQL
* MongoDB
* Redis
* Database Design
* SQL Queries
* Joins & Subqueries
* Indexing
* Transactions
* Database-per-Service Pattern

### 🎨 Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge\&logo=css3\&logoColor=white)

* React.js
* TypeScript
* JavaScript
* HTML5
* CSS3
* Bootstrap
* Tailwind CSS
* Component-Based UI Development

### ☁️ DevOps & Tools

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge\&logo=apachemaven\&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge\&logo=postman\&logoColor=white)

* Git & GitHub
* Docker
* Docker Compose
* Maven
* Postman
* Swagger / OpenAPI
* IntelliJ IDEA
* VS Code
* GitHub Actions
* CI/CD Fundamentals

---

# 🚀 Featured Projects

## 🏗️ BuildFlow — Construction Management & Intelligence Platform

> A real-world construction operations platform designed to help contractors manage projects, workforce, materials, equipment and finances in one system.

### 💡 Problem

Small construction contractors often manage:

* Worker attendance
* Daily wages
* Material purchases
* Cement & steel inventory
* Equipment expenses
* Project investments
* Client payments
* Project profit & loss

using notebooks, spreadsheets and manual calculations.

### 💡 Solution

**BuildFlow** digitizes these operations into a centralized platform that provides better visibility into project-level costs, resources and financial performance.

### ⚙️ Architecture

```text
                    ┌─────────────────┐
                    │   React + TS    │
                    │    Frontend     │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │   API Gateway   │
                    └────────┬────────┘
                             │
          ┌──────────────────┼──────────────────┐
          ▼                  ▼                  ▼
   ┌─────────────┐    ┌─────────────┐    ┌─────────────┐
   │   Project   │    │  Workforce  │    │   Material  │
   │   Service   │    │   Service   │    │   Service   │
   └─────────────┘    └─────────────┘    └─────────────┘
          │                  │                  │
          └──────────────────┼──────────────────┘
                             ▼
                    ┌─────────────────┐
                    │ Finance Service │
                    └─────────────────┘

              Kafka → Event Communication
              MySQL → Service Databases
              Redis → Caching / Analytics
```

### 🔧 Technologies

`Java` `Spring Boot` `Microservices` `React` `TypeScript` `MySQL` `REST APIs` `Apache Kafka` `Redis` `Docker` `Spring Security` `JWT`

### 🎯 Key Modules

* 🔐 Authentication & User Management
* 🏗️ Project Management
* 👷 Workforce & Attendance
* 📦 Material & Inventory Management
* 🚜 Equipment Management
* 💰 Finance & Expense Management
* 📊 Reporting & Analytics
* 🔔 Notification Management

🔗 **Repository:** Explore the BuildFlow project in my GitHub repositories.

---

## 🛒 E-commerce Microservices Platform

> A distributed e-commerce backend built to demonstrate real-world microservices architecture and backend engineering practices.

### 🧩 Microservices

```text
                   ┌──────────────────┐
                   │   API Gateway    │
                   └────────┬─────────┘
                            │
       ┌────────────┬───────┼────────┬─────────────┐
       ▼            ▼       ▼        ▼             ▼
    User         Product   Cart     Order        Payment
   Service       Service  Service  Service       Service
                              │
                              ▼
                       Notification
                          Service
```

### ✨ Key Features

* RESTful microservices
* JWT-based authentication
* Spring Security
* Database-per-service architecture
* Apache Kafka for asynchronous communication
* Redis caching
* MySQL databases
* API Gateway
* Docker & Docker Compose
* Centralized exception handling
* Input validation
* API documentation
* CI/CD using GitHub Actions

### 🔧 Technologies

`Java` `Spring Boot` `Spring Security` `JWT` `Kafka` `Redis` `MySQL` `Docker` `REST APIs` `GitHub Actions`

🔗 **Repository:** `ecommerce-microservices-platform`

---

# 📚 Other Projects

### 🎓 Student Management System

A CRUD-based application for managing student information.

**Technologies:** Java • Spring Boot • MySQL • React

### 🔗 REST API Applications

Backend applications demonstrating:

* REST API development
* CRUD operations
* Database integration
* Exception handling
* Request validation
* API testing with Postman

**Technologies:** Java • Spring Boot • MySQL • Hibernate • Postman

---

# 🧠 Currently Learning

```text
Java
 ├── OOP
 ├── Collections
 ├── Exception Handling
 ├── Multithreading
 ├── Java 8+
 └── Advanced Java

Spring Boot
 ├── REST APIs
 ├── Spring Security
 ├── JWT
 ├── JPA / Hibernate
 └── Microservices

Distributed Systems
 ├── Kafka
 ├── Redis
 ├── API Gateway
 ├── Resilience
 └── Observability

Problem Solving
 ├── Data Structures
 ├── Algorithms
 ├── SQL
 └── System Design

Frontend
 ├── React
 └── TypeScript
```

---

# 📊 GitHub Statistics

<p align="center">

<img src="https://github-readme-stats.vercel.app/api?username=sushmitha-katika-dev&show_icons=true&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=sushmitha-katika-dev&theme=tokyonight&hide_border=true" />

</p>

<p align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sushmitha-katika-dev&layout=compact&theme=tokyonight&hide_border=true" />

</p>

---

# 📈 What I'm Working Toward

```text
                 JAVA BACKEND ENGINEER
                          │
        ┌─────────────────┼─────────────────┐
        │                 │                 │
        ▼                 ▼                 ▼
   Backend Dev       Distributed       Problem Solving
        │              Systems               │
        ▼                 ▼                 ▼
 Spring Boot          Kafka / Redis          DSA
        │                 │                 │
        └─────────────────┼─────────────────┘
                          ▼
                  Production-Ready
                     Applications
```

My goal is to build software that is not only functional, but also **scalable, secure, maintainable and production-ready**.

---

# 📄 Resume

📎 **View / Download my Resume:**
[Resume](https://github.com/sushmitha-katika-dev/sushmitha-katika-dev/raw/main/Sushmitha_Katika_Resume.pdf)

---

# 🤝 Let's Connect

<p align="left">

<a href="https://www.linkedin.com/in/sushmitha-katika-1aa1b9262">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/sushmitha-katika-dev">
<img src="https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="mailto:katikasushmitha7228@gmail.com">
<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</p>

---

### 👀 Profile Views

![](https://komarev.com/ghpvc/?username=sushmitha-katika-dev\&style=for-the-badge)

---

⭐ **Thanks for visiting my profile!**

If you're interested in backend engineering, distributed systems, Java, or building real-world software products, feel free to explore my repositories and connect with me.
