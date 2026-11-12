# Employee Management System (Çalışan İşlemleri)

*Note: This project was developed as a practical application of concepts learned during a Udemy Java course to strengthen my skills in desktop UI development, database management, and JDBC integration.*

A robust desktop application built with Java Swing and MySQL that performs full CRUD (Create, Read, Update, Delete) operations for employee management. The system includes a secure admin login panel and a dynamic employee data table with real-time search filtering.

## Features

* **Secure Admin Login:** Verifies administrator credentials against the database before granting access to the management panel.
* **Full CRUD Operations:** Administrators can easily add new employees, update existing records, delete former employees, and read the entire database.
* **Dynamic Search Filter:** A real-time search bar that instantly filters the employee table based on names, departments, or other attributes as the user types.
* **Database Security:** Utilizes `PreparedStatement` for all SQL queries to ensure data integrity and prevent SQL Injection attacks.
* **Interactive GUI:** Developed using Java Swing, featuring clear input fields, responsive tables, and intuitive action buttons.

## Tech Stack

* **Language:** Java (JDK 8+)
* **UI Framework:** Java Swing
* **Database:** MySQL
* **Connectivity:** JDBC (Java Database Connectivity)

## How to Run the Application

1. Clone this repository to your local machine.
2. **Database Setup:** 
   * Open XAMPP, MAMP, or MySQL Workbench.
   * Create a new database named `demo`.
   * Import the provided `demo.sql` file to automatically set up the `adminler` and `calisanlar` tables along with sample data.
3. **Database Configuration:** Open `Database.java` and ensure the `host`, `port`, `username`, and `password` variables match your local MySQL configuration (Default: localhost, 3306, root, empty password).
4. **Run:** Execute the `GirisEkrani.java` file.
5. Log in using the admin credentials provided in the `adminler` table (e.g., username: `admin`, password: `admin`).
