# Spring Boot Dependency Injection

## 📌 Description

A simple Spring Boot project that demonstrates **Dependency Injection (DI)** and **Inversion of Control (IoC)** using `Car` and `Engine` classes.

Spring automatically creates and manages the objects and injects the required dependency.

## 🛠️ Technologies Used

* Java
* Spring Boot
* Maven
* VS Code
* Git & GitHub

## 📂 Project Structure

```text
src/
└── main/
    ├── java/
    │   └── com.example.demo/
    │       ├── DemoApplication.java
    │       ├── Car.java
    │       └── Engine.java
    │
    └── resources/
        └── application.properties

pom.xml
README.md
```

## 🔄 Dependency Injection

In this project, `Car` depends on `Engine`.

Spring creates the `Engine` object and injects it into the `Car` object.

```text
Spring Container
      ↓
Creates Engine
      ↓
Creates Car
      ↓
Injects Engine into Car
```

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/bhagya-lakshmi24/spring-boot-dependency-injection.git
```

2. Open the project in VS Code or any Java IDE.

3. Run the Spring Boot application:

```bash
mvn spring-boot:run
```

## 🎯 Learning Outcomes

* Understanding Spring Boot basics
* Understanding IoC and Dependency Injection
* Creating and managing Spring beans
* Understanding Maven project structure
* Running a Spring Boot application

## 👩‍💻 Author

**Bhagyalakshmi**

B.Tech Computer Science Engineering Student
