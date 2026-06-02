# 🎓 Smart Campus Information System

A Python-based console application designed to manage student information, course enrollment, fee calculation, file management, and performance analytics within a campus environment.

This project demonstrates the practical implementation of Python programming concepts including data structures, file handling, exception handling, data analytics, and visualization.

---

## 📌 Project Overview

The **Smart Campus Information System** is an integrated academic management application that enables users to:

* Register students
* Calculate grades automatically
* Enroll students in courses
* Search and display student records
* Generate rank lists
* Calculate fees
* Save and retrieve records from files
* Scan directories
* Perform student performance analytics
* Visualize performance using charts

---

## 🚀 Features

### 1. Student Registration

* Register students using USN and Name.
* Enter marks for three subjects.
* Automatically calculate average marks.
* Automatically assign grades.

### 2. Grade Evaluation

| Average Marks | Grade |
| ------------- | ----- |
| 90 and above  | A+    |
| 80 – 89       | A     |
| 70 – 79       | B     |
| 60 – 69       | C     |
| Below 60      | F     |

---

### 3. Course Enrollment

Available Courses:

* Python Programming
* Data Structures
* AI Fundamentals
* Database Systems

Students can be assigned to any available course.

---

### 4. Student Record Management

* Display all student records
* Search student by USN
* View marks and grades
* Display enrolled courses

---

### 5. Rank List Generation

Students are automatically sorted based on average marks.

Features:

* Ranking of students
* Highest scorer identification
* Performance comparison

---

### 6. Fee Calculation

Calculates total fee by combining:

* Tuition Fee
* Laboratory Fee
* Examination Fee

Formula:

```text
Total Fee = Tuition Fee + Lab Fee + Exam Fee
```

---

### 7. File Handling

#### Save Records

Stores student data in:

```text
student_records.txt
```

#### Read Records

Retrieves and displays previously saved records.

---

### 8. Directory Scanner

Allows users to:

* Scan a folder path
* Display all files in the directory
* Handle invalid paths safely

Exception handling included for:

* FileNotFoundError
* PermissionError
* General exceptions

---

### 9. Performance Analytics

The system uses:

* NumPy
* Pandas
* Matplotlib

Analytics Provided:

* Highest Average
* Lowest Average
* Class Average

Visualization:

* Student Performance Bar Chart

---

## 🛠️ Technologies Used

### Programming Language

* Python 3.x

### Libraries

* NumPy
* Pandas
* Matplotlib
* OS Module

### Concepts Implemented

* Functions
* Lists
* Dictionaries
* Sorting
* Searching
* File Handling
* Exception Handling
* Data Analysis
* Data Visualization

---

## 📂 Project Structure

```text
Smart-Campus-Information-System/
│
├── main.py
├── student_records.txt
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

### Step 1: Clone Repository

```bash
git clone https://github.com/your-username/smart-campus-information-system.git
```

### Step 2: Move into Project Directory

```bash
cd smart-campus-information-system
```

### Step 3: Install Dependencies

```bash
pip install numpy pandas matplotlib
```

---

## ▶️ Running the Project

```bash
python main.py
```

---

## 📋 Main Menu

```text
==================================================
SMART CAMPUS INFORMATION SYSTEM
==================================================

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
```

---

## 📊 Sample Output

### Student Registration

```text
Enter USN : 1RV21CS001
Enter Name : Rahul

Enter Subject 1 Marks : 85
Enter Subject 2 Marks : 90
Enter Subject 3 Marks : 88

Student Registered Successfully
Grade Awarded : A
```

---

### Rank List

```text
===== RANK LIST =====

1 Rahul - 87.67
2 Priya - 84.33
3 Arjun - 79.00
```

---

### Analytics

```text
===== ANALYTICS =====

Highest Average : 92.5
Lowest Average  : 68.3
Class Average   : 81.2
```

---

## 🎯 Learning Outcomes

This project helps in understanding:

* Student Information Management Systems
* Python Programming Fundamentals
* Data Processing using NumPy
* Data Analysis using Pandas
* Visualization using Matplotlib
* File Operations and Exception Handling

---

## 🔮 Future Enhancements

* GUI using Tkinter or PyQt
* SQLite/MySQL Database Integration
* Attendance Management Module
* Faculty Management Module
* Authentication and Login System
* PDF Report Generation
* Web Application Version using Flask/Django
* Cloud Data Storage

---

## 👨‍💻 Author

**Smart Campus Information System**

Developed as a Mini Project for demonstrating Python-based Academic Management and Analytics.

---

## 📜 License

This project is developed for educational and academic purposes.
