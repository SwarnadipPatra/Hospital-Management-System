# Hospital Management System (Java + MySQL)

A simple Hospital Management System built using Core Java, MySQL, JDBC, and IntelliJ IDEA. The project allows managing patients, doctors, and appointments using a console-based menu system.

## 🏷️ Technologies & Tools

- Java (Core Java)
- MySQL Database
- JDBC (MySQL Connector)
- IntelliJ IDEA

## ✨ Features

- Add new patients
- View patient details
- View doctor list
- Book appointments
- Store data in MySQL database using JDBC

## 📌 Database Details

- Database name: hospital
- SQL script included: database.sql

The project includes the following tables:

- patients
- doctors
- appointments

## ▶️ How to Run the Project

1. Install Java JDK  
2. Install MySQL Server or MySQL Workbench  
3. Open the project in IntelliJ IDEA  
4. Execute `database.sql` in MySQL to create the `hospital` database  
5. Download the MySQL JDBC Connector JAR file  
6. Add the JAR to the project libraries in IntelliJ IDEA  
7. Update database credentials in the code:
   - URL: `jdbc:mysql://localhost:3306/hospital`
   - Username: your MySQL username
   - Password: your MySQL password
8. Run the main class `HospitalManagementSystem.java`

## 📂 Project Files

- Doctor.java
- Patient.java
- HospitalManagementSystem.java
- database.sql
- README.md

## 👨‍💻 Author

- Swarnadip Patra
