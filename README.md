# Product Management System

## Overview
The **Product Management System** is a web application designed to manage product-related information, including adding, editing, viewing, and deleting product details. The project is developed using **Spring Framework**, **JPA (Hibernate)**, and **JSP** for the frontend. 

## Features
- Add new products with details like name, description, price, and category.
- View all products in a table format.
- Edit product information.
- Delete products from the database.
- Login functionality to restrict unauthorized access.

## Technologies Used
- **Backend:** Spring Framework (Spring Boot), Hibernate (JPA)
- **Frontend:** JSP, HTML, CSS
- **Database:** MySQL
- **Build Tool:** Maven
- **Server:** Apache Tomcat

## Prerequisites
- JDK 11 or later
- Maven 3.6 or later
- MySQL database
- Git

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/gousepashaa/Product_Management.git
   
2. Navigate to the project directory:
    cd Product_Management
   
4. Import the project into your IDE (e.g., Eclipse or IntelliJ) as a Maven project.
   
5. Configure the database:
   * Update the application.properties file with your MySQL credentials:
    properties
    spring.datasource.url=jdbc:mysql://localhost:3306/your_database
    spring.datasource.username=your_username
    spring.datasource.password=your_password
   
6. Build and run the application:
    bash
    mvn clean install
    mvn spring-boot:run

Usage
1. Navigate to the login page at http://localhost:8080/login.
2. Log in using valid credentials.
3. Add, view, edit, or delete products using the respective pages.

Project Structure
bash
Copy code
src/
├── main/
│   ├── java/
│   │   ├── pm/Controller/
│   │   ├── pm/Service/
│   │   ├── pm/dao/
│   │   ├── pm/dto/
│   ├── resources/
│   │   ├── application.properties
│   ├── webapp/
│       ├── WEB-INF/
│       │   ├── jsp/
│       │       ├── login.jsp
│       │       ├── home.jsp
│       │       ├── products.jsp
│       │       ├── add-product.jsp
├── pom.xml


## Contributing
   Contributions are welcome! Please fork the repository and submit a pull request for review.

## License
   This project is licensed under the MIT License.
