Student Management System
A SQL-based system designed to manage student records, courses, enrollments, and grades. This project demonstrates database design, triggers, stored procedures, and views using MySQL.
Features

Manage student information (ID, name, email, enrollment date).
Track courses with credits and student enrollments.
Record and monitor grades with a logging trigger.
Calculate GPA using a stored procedure.
Provide a performance summary view.

How to Set Up

Ensure MySQL is installed and running (e.g., via Homebrew on macOS: brew services start mysql).
Log in to MySQL:mysql -u root -p


Create and use the database:SOURCE StudentManagement.sql;


Verify the setup:USE StudentManagement;
SHOW TABLES;
SELECT * FROM StudentPerformance;



Files

StudentManagement.sql: Contains the database schema, triggers, stored procedures, and sample data.

