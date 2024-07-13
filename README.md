# sunbaseproject

# Spring Boot CRUD Application with JWT Authentication

This project is a simple CRUD (Create, Read, Update, Delete) application for managing customer data. It includes backend APIs implemented with Spring Boot and frontend pages using HTML, CSS, and JavaScript.

## Features

- **Backend APIs:**
  - Create, Update, Delete a customer.
  - Retrieve a list of customers with pagination, sorting, and searching.
  - Retrieve a single customer by ID.
  - JWT Authentication for securing APIs.

- **Frontend Pages:**
  - Login Screen: Allows users to authenticate using JWT.
  - Customer List Screen: Displays a list of customers with options to edit, delete, and sync data.
  - Add New Customer Screen: Allows users to add a new customer or edit an existing one.

- **Additional Features (Phase 2):**
  - Sync Button: Fetches customer data from a remote API and syncs it with the local database.
  - API Authentication: Authenticates users using provided credentials via a POST request.

## Technologies Used

- **Backend:**
  - Java
  - Spring Boot
  - Spring Security (JWT Authentication)
  - MySQL (or your preferred database)

- **Frontend:**
  - HTML
  - CSS
  - JavaScript

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed (version 8 or higher)
- Maven build tool
- MySQL database (or another database supported by Spring Boot)
- IDE (Eclipse, IntelliJ IDEA, etc.)

### Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Sa-heal/sunbaseproject.git
   cd sunbaseproject
   
2. **Database Configuration:**

Create a MySQL database and update the application.properties file with your database credentials:

spring.datasource.url=jdbc:mysql://localhost:3306/db_name

spring.datasource.username=db_username

spring.datasource.password=db_password

3. **Build and Run the Application:**

Build the application using Maven:

mvn clean package

4. **Run the application:**

java -jar target/your-application.jar
Alternatively, you can run the application directly from your IDE by running the main class (Application.java).

5. **Access the Application:**

Open a web browser and navigate to http://localhost:8080/login.html to access the login page.

6. **Login Credentials:**

Use the following credentials to log in:
Username: test@sunbasedata.com
Password: Test@123

7. **Explore the Application:**

After logging in, you can navigate through the customer list, add new customers, edit existing ones, and sync data from the remote API.


Author
Sahil Lanjewar.
