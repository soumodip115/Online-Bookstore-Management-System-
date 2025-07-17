# Online-Bookstore-Management-System-
Online Bookstore - Spring Boot Application
This is a full-stack web application for an Online Bookstore, built using the Spring Boot framework. The system allows users to browse and purchase books, and provides a secure administrative panel for managing the store's inventory and customer orders.

The project is built with a clean, layered architecture (Controller-Service-Repository) and demonstrates key features of the Spring ecosystem, including Spring MVC, Spring Data JPA, and Spring Security.

🚀 Features
Customer-Facing Features
Browse & Search: Users can browse a paginated list of all available books.

Search Functionality: Users can search for books by their title.

Shopping Cart: A session-based shopping cart allows users to add, remove, and view items.

Checkout Process: A complete checkout process where users can enter their billing details to place an order.

Admin Panel Features
Secure Login: The admin panel is protected by a login page.

Book Management (CRUD): Administrators can Create, Read, Update, and Delete books from the inventory.

Order Management: Administrators can view a complete list of all customer orders.

Search Orders: Admins can search for specific orders by date.

🛠️ Tech Stack
Framework: Spring Boot 2.6.6

Language: Java 11

Build Tool: Maven

Web: Spring MVC, Thymeleaf

Data Persistence: Spring Data JPA, Hibernate

Database: H2 In-Memory Database

Security: Spring Security

Testing: JUnit 5, Mockito, AssertJ

Frontend: HTML, CSS, Bootstrap

⚙️ Getting Started
Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

Prerequisites
Java JDK 11 or later

Apache Maven

Installation & Setup
Clone the repository:

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

Run the application:
You can run the application using the Spring Boot Maven plugin.

mvn spring-boot:run

The application will start on http://localhost:8080.

Access the Application:

Homepage: Open your browser and go to http://localhost:8080

H2 Database Console: To view the in-memory database, go to http://localhost:8080/h2-console. Use the credentials from the application.properties file:

JDBC URL: jdbc:h2:mem:bookstore

User Name: crni99

Password: og

Admin Credentials
To access the administrative panel, use the following credentials which are pre-loaded from the data.sql file:

Username: admin

Password: admin

🏛️ Project Architecture
The application follows a standard layered architecture to ensure a separation of concerns and maintainable code.

com.crni99.bookstore.controller: Handles incoming HTTP requests and directs them to the appropriate service.

com.crni99.bookstore.service: Contains the core business logic of the application.

com.crni99.bookstore.repository: Manages data access using Spring Data JPA interfaces.

com.crni99.bookstore.model: Defines the JPA entity classes that map to database tables.

com.crni99.bookstore.security: Contains the Spring Security configuration for authentication and authorization.


