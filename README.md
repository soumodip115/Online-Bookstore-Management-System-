Online Bookstore - Spring Boot MVC Project
A full-stack web application built with the Spring Framework that simulates a real-world online bookstore. This project demonstrates a classic Model-View-Controller (MVC) architecture and showcases core Spring concepts like Dependency Injection, Spring Data JPA for database communication, and Spring Security for authentication and authorization.

The application provides a seamless user experience for customers to browse, search, and purchase books, alongside a secure and functional administrative panel for managing the store's inventory and viewing customer orders.

🚀 Core Features
👤 Customer Features
Book Catalog: Browse a paginated list of all available books.

Search: Find specific books by searching for their titles.

Shopping Cart: A fully functional, session-based cart to add or remove books before purchase.

Checkout: A multi-step checkout process to enter billing information and place an order.

🔐 Admin Features
Secure Authentication: A dedicated login portal for administrators.

Dashboard: A central panel to manage books and view orders.

Full CRUD Functionality: Administrators can Create, Read, Update, and Delete books in the inventory.

Order Management: View a complete history of all customer orders, with the ability to search by date and view specific order details.

🛠️ Technology Stack
This project is built with a robust and modern set of tools and technologies:

Backend:

Spring Boot: For rapid, convention-over-configuration application development.

Spring MVC: For building the web application layer following the MVC pattern.

Spring Data JPA: To simplify data access and reduce boilerplate code.

Spring Security: For handling user authentication and role-based authorization.

Frontend:

Thymeleaf: A modern server-side Java template engine for creating dynamic HTML views.

Bootstrap: For responsive and clean UI components.

HTML5 & CSS3

Database:

H2 In-Memory Database: For ease of development and testing without external database setup.

Hibernate: The JPA implementation for object-relational mapping.

Build & Testing:

Maven: For dependency management and project build lifecycle.

JUnit 5 & Mockito: For comprehensive unit testing of service and controller layers.

⚙️ Getting Started
Follow these instructions to get a copy of the project up and running on your local machine.

Prerequisites
Java Development Kit (JDK) 11 or newer.

Apache Maven.

An IDE like IntelliJ IDEA or VS Code.

Installation & Execution
Clone the Repository

git clone https://github.com/soumodip115/Online-Bookstore-Management-System-.git
cd Online-Bookstore-Management-System-

Run the Application with Maven
Navigate to the project's root directory in your terminal and use the Spring Boot Maven plugin to start the application.

mvn spring-boot:run

The server will start on port 8080.

Access the Application

Homepage: http://localhost:8080

Admin Panel: http://localhost:8080/book (You will be redirected to the login page)

H2 Database Console: http://localhost:8080/h2-console

📋 Usage and Configuration
Admin Credentials
The application is pre-loaded with a default administrator account. Use these credentials to log in to the admin panel:

Username: admin

Password: admin

(These credentials are set in the src/main/resources/db/data.sql file).

H2 Database Console
You can view the contents of the in-memory database through the H2 console. Use the following settings from src/main/resources/application.properties to connect:

Driver Class: org.h2.Driver

JDBC URL: jdbc:h2:mem:bookstore

User Name: crni99

Password: og
