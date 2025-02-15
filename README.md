# Student Management System

## Overview
The **Student Management System** is a web-based application developed using **Spring Boot** and **Maven**. 
It allows administrators to manage student records, including adding, updating, viewing, and deleting student information.

## Features
- Add new students with essential details
- Update student information
- View a list of all students
- Delete student records

## Technologies Used
- **Java 17**
- **Spring Boot**
- **Maven** (Build Tool)
- **MySQL** (Database)
- **Thymeleaf** (Frontend Templating)
- **Spring Data JPA** (ORM)
- **Spring MVC** (Web Framework)

## Installation and Setup

### Prerequisites
Ensure you have the following installed:
- **Java 17**
- **Maven**
- **MySQL**

### Steps to Set Up
1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd student-management-system-main
   ```
2. Configure the database in `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/student_db
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   ```
3. Install dependencies and build the project:
   ```sh
   mvn clean install
   ```
4. Run the application:
   ```sh
   mvn spring-boot:run
   ```
5. Access the application in your browser:
   ```
   http://localhost:8080
   ```

## API Endpoints
| Endpoint             | Method | Description            |
|----------------------|--------|------------------------|
| `/students`         | GET    | View all students      |
| `/students/add`     | POST   | Add a new student      |
| `/students/update`  | PUT    | Update student details |
| `/students/delete`  | DELETE | Remove a student       |

## Contributing
Feel free to fork the repository and submit pull requests. Make sure to follow coding standards and document your changes properly.

## License
This project is licensed under the **MIT License**.

## Contact
For any queries, reach out to **Akshay Reddy G** at:
- **Email:** akshayreddygolamari@gmail.com
- **LinkedIn:** [Profile](https://www.linkedin.com/in/akshayreddy)
- **GitHub:** [Account](https://github.com/akshayreddy1906)

---
**Happy Coding!** 🚀

