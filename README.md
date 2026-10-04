\# Spring Boot Dependency Injection



\## 📌 Project Description



This project demonstrates the core concepts of \*\*Dependency Injection (DI)\*\* and \*\*Inversion of Control (IoC)\*\* using \*\*Spring Boot\*\*.



The project uses a simple `Car` and `Engine` example to show how Spring automatically creates, manages, and injects dependent objects instead of creating them manually using the `new` keyword.



\## 🛠️ Technologies Used



\* \*\*Java\*\*

\* \*\*Spring Boot\*\*

\* \*\*Maven\*\*

\* \*\*Spring Core / IoC Container\*\*

\* \*\*Dependency Injection\*\*

\* \*\*VS Code\*\*

\* \*\*Git \& GitHub\*\*



\## 🔄 Dependency Injection



Dependency Injection is a design principle where an object's required dependencies are provided by an external framework instead of the object creating them itself.



In this project:



```text

Car

&#x20;↓

requires

&#x20;↓

Engine

```



Spring manages the `Engine` object and injects it into the `Car` object.



\### Without Dependency Injection



```java

Engine engine = new Engine();

Car car = new Car(engine);

```



Here, the programmer manually creates the dependency.



\### With Spring Dependency Injection



Spring creates and manages the objects:



```text

Spring Boot Application

&#x20;       ↓

&#x20;  Spring Container

&#x20;       ↓

&#x20;  Creates Engine

&#x20;       ↓

&#x20;  Creates Car

&#x20;       ↓

Injects Engine into Car

```



This reduces tight coupling and makes the application easier to maintain and test.



\## 📂 Project Structure



```text

spring-boot-dependency-injection/

│

├── src/

│   └── main/

│       ├── java/

│       │   └── com.example.demo/

│       │       ├── DemoApplication.java

│       │       ├── Car.java

│       │       └── Engine.java

│       │

│       └── resources/

│           └── application.properties

│

├── .gitignore

├── pom.xml

└── README.md

```



\## ▶️ How to Run the Project



\### 1. Clone the repository



```bash

git clone https://github.com/bhagya-lakshmi24/spring-boot-dependency-injection.git

```



\### 2. Open the project



Open the project in \*\*VS Code\*\*, IntelliJ IDEA, or Eclipse.



\### 3. Navigate to the project directory



```bash

cd spring-boot-dependency-injection

```



\### 4. Run the Spring Boot application



Using Maven:



```bash

mvn spring-boot:run

```



Or, if using the Maven Wrapper:



```bash

./mvnw spring-boot:run

```



On Windows:



```powershell

.\\mvnw.cmd spring-boot:run

```



\## 💻 Example Output



When the application starts successfully, the console displays Spring Boot startup information similar to:



```text

:: Spring Boot ::



Started DemoApplication in 1.XXX seconds

```



If the application contains a `Car` method that uses the injected `Engine`, the output can be:



```text

Car is running

Engine is running

```



\## 🎯 Learning Objectives



This project helps understand:



\* Spring Boot application structure

\* Inversion of Control (IoC)

\* Dependency Injection (DI)

\* Spring IoC Container

\* Spring-managed beans

\* Object creation and management by Spring

\* Maven project structure

\* Running a Spring Boot application



\## 🚀 Future Improvements



The project can be extended by adding:



\* REST APIs

\* Spring Data JPA

\* MySQL database integration

\* Service and Repository layers

\* Exception handling

\* Unit testing with JUnit

\* Spring Boot Actuator



\## 👩‍💻 Author



\*\*Bhagya Lakshmi\*\*



B.Tech Computer Science Engineering Student



GitHub: \[bhagya-lakshmi24](https://github.com/bhagya-lakshmi24)



