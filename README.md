# AcademiCore: Centralized Attendance and Subject Hub

AcademiCore is a comprehensive system designed to manage student attendance and academic records efficiently. Developed using Spring Boot and Hibernate, the project follows a layered architecture to ensure scalability and maintainability. It integrates MySQL for data storage and provides RESTful APIs for seamless interaction and operations.

---

## Features

- Manage student attendance records: add, update, view, and delete entries.  
- Maintain academic performance records with CRUD operations.  
- Expose RESTful APIs for interaction with attendance and subject data.  
- Ensure reliability and data consistency through thorough API testing with Postman.  

---

## Tech Stack

- **Backend Framework**: Spring Boot  
- **ORM**: Hibernate  
- **Database**: MySQL  
- **Tools**: Maven for dependency management and Postman for API testing  

---

## Project Architecture

AcademiCore is structured as follows:  

- **Controller Layer**: Handles HTTP requests and provides RESTful APIs for client interaction.  
- **Service Layer**: Implements business logic and communicates with the DAO layer.  
- **DAO Layer**: Executes CRUD operations with the database using Hibernate.  
- **Entity Layer**: Maps database tables to Java classes for object-relational mapping.


 
 StudentAttendanceManagementSystem/ ├── src/ │ ├── main/ │ │ ├── java/ │ │ │ ├── com/ │ │ │ │ ├── controller/ │ │ │ │ │ └── StudentController.java │ │ │ │ │ └── AttendanceController.java │ │ │ │ ├── dao/ │ │ │ │ │ └── StudentDAO.java │ │ │ │ │ └── AttendanceDAO.java │ │ │ │ ├── entity/ │ │ │ │ │ └── Student.java │ │ │ │ │ └── Attendance.java │ │ │ │ ├── service/ │ │ │ │ │ └── StudentService.java │ │ │ │ │ └── AttendanceService.java │ │ │ └── utility/ │ │ │ └── DatabaseConnection.java ├── pom.xml ├── README.md

---

## Key Functionalities

1. **Manage Attendance Records**  
   - Add, update, and delete attendance records for students.  
   - Fetch attendance records by criteria, such as student ID or date range.  

2. **Manage Academic Records**  
   - Store, retrieve, and update academic performance details for students.  
   - Delete records as required.  

3. **RESTful APIs**  
   - Expose APIs for seamless integration with external systems or UI components.  

4. **API Testing**  
   - Thoroughly test all endpoints using Postman to ensure consistency and functionality.  



