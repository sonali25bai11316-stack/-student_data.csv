 Student Database Management System

Problem Statement
Educational institutions and teachers often struggle with managing student records manually using paper or complex software. There is a need for a lightweight, cost-effective, and easy-to-use digital solution that allows for the quick storage, retrieval, and modification of student academic data without requiring internet connectivity or SQL database knowledge.


Scope of the Project
The scope of this project is limited to a Console-Based Application that performs CRUD (Create, Read, Update, Delete) operations
Data Storage: Uses a local CSV file (student_data.csv) for persistence
Interface: Command Line Interface (CLI)
Functionality: strictly limited to basic details (Roll No, Name, Class, Marks)


Target Users
School Teachers: For maintaining small class records
Lab Admins: For tracking student attendance or basic info
Computer Science Students: As a learning resource for Python file handling and logic building


High-Level Features
Menu-Driven Interface: User-friendly text menu for navigation
Duplicate Prevention: Logic to ensure unique Roll Numbers
Updates: Ability to update specific fields while keeping others unchanged
Formatting: Dynamic alignment of text for better readability on the console
Error Handling: Prevents crashes if the database file is missing or inputs are invalid