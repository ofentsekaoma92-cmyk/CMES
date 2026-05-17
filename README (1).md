# TechnoByteSolutionsApp

A Java web application built using JSP, Servlets, Maven, and MySQL. The application provides a dashboard for monitoring company projects and student engagement statistics.

---

## 👨‍💻 Developer

**GitHub:** https://github.com/ofentsekaoma92

---

## 📌 Project Overview

TechnoByteSolutionsApp is a Maven-based Java EE web application that demonstrates:

- Java Servlets
- JSP pages
- MVC-style structure
- Database connectivity using MySQL
- DAO (Data Access Object) pattern
- Dynamic dashboard statistics

The application allows users to:

- View company statistics
- View project statistics
- Track student engagement/views
- Navigate through a simple web dashboard

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Java 8 | Backend development |
| JSP | Frontend rendering |
| Servlets | Request handling |
| Maven | Project management |
| MySQL | Database management |
| JDBC | Database connectivity |
| Apache Tomcat / GlassFish | Application server |
| HTML & CSS | User interface |

---

## 📂 Project Structure

```text
TechnoByteSolutionsApp
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/technobytesolutions/
│   │   │       ├── dao/
│   │   │       ├── model/
│   │   │       ├── servlet/
│   │   │       └── util/
│   │   │
│   │   ├── webapp/
│   │   │   ├── index.jsp
│   │   │   ├── dashboard.jsp
│   │   │   └── WEB-INF/
│   │   │       └── web.xml
│   │
├── pom.xml
└── README.md
```

---

## ⚙️ Features

### 🏢 Company Statistics
Displays the total number of companies stored in the database.

### 📁 Project Statistics
Displays the total number of projects available.

### 👨‍🎓 Student Engagement
Tracks and displays the number of students who viewed projects.

### 📊 Dashboard Interface
A responsive dashboard showing system statistics in card format.

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/ofentsekaoma92/TechnoByteSolutionsApp.git
```

### 2️⃣ Open the Project

Open the project using:

- NetBeans
- IntelliJ IDEA
- Eclipse

---

### 3️⃣ Configure the Database

Create a MySQL database.

Example:

```sql
CREATE DATABASE technobytesolutions;
```

Update your database connection settings inside the database utility class.

Example configuration:

```java
String url = "jdbc:mysql://localhost:3306/technobytesolutions";
String username = "root";
String password = "your_password";
```

---

### 4️⃣ Build the Project

Using Maven:

```bash
mvn clean install
```

---

### 5️⃣ Deploy the WAR File

Deploy the generated WAR file to:

- Apache Tomcat
- GlassFish Server

Generated WAR file:

```text
TechnoByteSolutionsApp.war
```

---

## 🧱 Design Pattern Used

### MVC Architecture

- **Model** → Handles application data
- **View** → JSP pages
- **Controller** → Java Servlets

### DAO Pattern

Used to separate database operations from business logic.

---

## 🎯 Learning Objectives

This project demonstrates:

- Java EE web development
- Database integration using JDBC
- Maven project setup
- Servlet-to-JSP communication
- MVC application architecture
- DAO implementation

---

## 🔮 Possible Improvements

Future enhancements may include:

- User authentication
- CRUD functionality
- Admin panel
- REST API integration
- Improved UI using Bootstrap
- Search and filtering
- Data visualization charts

---

## 📜 License

This project is for educational and learning purposes.

---

## ⭐ GitHub

If you found this project useful, consider starring the repository.

GitHub Profile:
https://github.com/ofentsekaoma92
