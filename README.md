# Java Servlet-JSP Login System

A simple login and registration system using Java Servlets, JSP, JDBC, and MySQL.

##  Features
- User registration with form validation
- Login with session tracking
- MVC-based folder structure
- JDBC connection to MySQL

##  Technologies Used
- Java (JDK 8+)
- JSP & Servlets (Jakarta EE)
- MySQL
- Apache Tomcat
- JDBC

##  Project Structure


src/
├── in.sp.controller.RegisterServlet
├── in.sp.controller.LoginServlet
├── in.sp.model.User
├── in.sp.db.DbConnection




##  Setup Instructions
1. Create MySQL DB `yourdb` and table `users`
2. Update `DbConnection.java` with your DB credentials
3. Import project as Dynamic Web Project in Eclipse
4. Add MySQL JDBC connector to build path
5. Run on Tomcat



# Java Servlet-JSP Login & Registration System

A simple full-stack web application built using **Java Servlets**, **JSP**, and **JDBC**, demonstrating a classic **MVC (Model-View-Controller)** pattern for user registration and login.

---

## Features

- ✅ User registration with form inputs
- ✅ Login authentication with session handling
- ✅ JDBC-based MySQL database connection
- ✅ Modular MVC project structure
- ✅ Built and deployed via Apache Tomcat

---

## Tech Stack

| Layer        | Technology                  |
|--------------|------------------------------|
| Frontend     | HTML, JSP                    |
| Backend      | Java Servlets (Jakarta EE)   |
| Database     | MySQL                        |
| DB Access    | JDBC                         |
| App Server   | Apache Tomcat (8.5 or later) |
| IDE          | Eclipse                      |

---

## Folder Structure

java-mvc-login-system/
├── WebContent/
│ ├── index.html
│ ├── login.html
│ ├── register.html
│ └── WEB-INF/web.xml
├── src/
│ └── in/sp/controller/
│ ├── RegisterServlet.java
│ └── LoginServlet.java
│ └── in/sp/db/
│ └── DbConnection.java
│ └── in/sp/model/
│ └── User.java




##  Author
Sharanya Nemade
