Student Database Management System

A simple, menu-driven Python program to manage student records efficiently. This project uses a CSV file to store data, allowing users to add, view, update, delete, and search for student information without needing a complex database server

Overview
This project was developed by SONALI to demonstrate file handling in Python, specifically using the csv module. It acts as a database system where data is saved even after the program is closed. It validates inputs (like duplicate roll numbers) and formats the output in a readable table.

Features

Add Student: Input details (Roll No, Name, Class, Marks) with duplicate validation
Display Records: Shows all students in a neat, tabular format
Search: Find specific student details using their Roll Number
Update: Modify details of an existing student
Delete: Remove a student record permanently
Data Persistence: All data is saved in student_data.csv

Technologies Used
Language: Python 3
Libraries: csv (Standard library), os (For file checks)
Editor: VS Code 

Steps to Install & Run

Clone the repository (or download the zip):
git clone [https://github.com/sonali25bai11316-stack/student-dbms.git]


Navigate to the project directory:
cd student-dbms


Run the script:
python student_dbms.csv.py
(Note: The student_data.csv file will be created automatically upon the first run)

Instructions for Testing

Start the App: Run the script.
Add Data: Choose option 1 and add a student (e.g., Roll: 1, Name: ak). Try adding Roll 1 again to test the duplicate check
View Data: Choose option 5 to see the table
Update: Choose option 2, enter Roll 1, and change the marks
Search: Choose option 4 and enter 1 to see the specific record
Delete: Choose option 3 to remove 1
Verify Delete: Choose option 5 again to confirm the list is empty (or the student is gone)

