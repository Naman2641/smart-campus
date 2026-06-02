# smart-campus


Smart Campus Information System

A Python-based console application for managing student records, course enrollment, fee calculations, file handling, directory scanning, and performance analytics. The project demonstrates the use of Python fundamentals, file handling, data structures, NumPy, Pandas, and Matplotlib in a real-world academic management system.

Features
1. Student Registration
Register students using USN and Name.
Enter marks for 3 subjects.
Automatically calculate average marks.
Automatically assign grades:
A+ : 90 and above
A : 80–89
B : 70–79
C : 60–69
F : Below 60
2. Course Enrollment

Students can enroll in courses such as:

Python Programming
Data Structures
AI Fundamentals
Database Systems
3. Student Record Management
Display all student records.
Search student by USN.
Sort students based on average marks.
Generate rank list.
4. Fee Calculation

Calculate total student fee by adding:

Tuition Fee
Lab Fee
Exam Fee
5. File Handling
Save student records to a text file.
Read saved records from file.
6. Directory Scanner
Scan any folder path.
Display all files present in the directory.
Handles file and permission errors.
7. Performance Analytics
Highest Average
Lowest Average
Class Average
Pandas DataFrame Representation
Bar Chart Visualization using Matplotlib
Technologies Used
Python 3.x
NumPy
Pandas
Matplotlib
OS Module
File Handling
Project Structure
Smart-Campus-Information-System/
│
├── main.py
├── student_records.txt
├── README.md
└── requirements.txt
Installation
Clone Repository
git clone https://github.com/yourusername/smart-campus-information-system.git
cd smart-campus-information-system
Install Dependencies
pip install numpy pandas matplotlib
Running the Program
python main.py
Menu Options
1. Student Registration
2. Course Enrollment
3. Display Student Records
4. Search Student
5. Sort Students
6. Fee Calculation
7. Save Records
8. Read Records
9. Directory Scanner
10. Performance Analytics
11. Exit
Sample Workflow
Register Student
Enter USN : 1RV21CS001
Enter Name : Rahul
Enter Subject 1 Marks : 85
Enter Subject 2 Marks : 90
Enter Subject 3 Marks : 88

Student Registered Successfully
Grade Awarded : A
Course Enrollment
Enter Student USN : 1RV21CS001
Enter Course Name : AI Fundamentals

Course Enrolled Successfully
Analytics Output

The analytics module provides:

Highest Average : 92.5
Lowest Average  : 68.3
Class Average   : 81.2

Along with:

Pandas DataFrame display
Student performance bar chart
Concepts Demonstrated
Functions
Lists and Dictionaries
Conditional Statements
Loops
File Handling
Exception Handling
Sorting
Data Analytics
Data Visualization
Python Libraries Integration
Future Enhancements
GUI using Tkinter/PyQt
Database Integration (MySQL/SQLite)
Student Login System
Attendance Management
Result Management
PDF Report Generation
Web-Based Dashboard
