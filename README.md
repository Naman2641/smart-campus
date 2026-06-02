<div align="center">

# 🏛️ Smart Campus Information System

**A Python-powered academic management platform for the modern campus**

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![NumPy](https://img.shields.io/badge/NumPy-Enabled-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
[![Pandas](https://img.shields.io/badge/Pandas-Enabled-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Enabled-11557c?style=for-the-badge)](https://matplotlib.org)
[![License](https://img.shields.io/badge/License-Educational-green?style=for-the-badge)](LICENSE)

> *Streamlining student registration, course enrollment, performance analytics, and file management — all in one elegant console application.*

</div>

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#️-tech-stack)
- [Project Structure](#-project-structure)
- [Installation](#️-installation)
- [Usage](#-usage)
- [Sample Output](#-sample-output)
- [Learning Outcomes](#-learning-outcomes)
- [Future Roadmap](#-future-roadmap)

---

## 🌟 Overview

The **Smart Campus Information System** is an integrated, Python-based console application that bridges academic administration with modern data analytics. Built as a showcase of core Python programming principles, it covers everything from student registration and grade calculation to performance visualization and file management.

Whether you're a student exploring Python's potential or an educator looking for a practical project reference, this system demonstrates real-world application of:

- 📊 Data structures & algorithms
- 🗂️ File handling & exception management
- 📈 Data analytics & visualization
- 🔍 Search, sort, and reporting pipelines

---

## ✨ Features

### 🎓 Student Registration
Effortlessly register students with USN and name, record marks across three subjects, and let the system automatically compute averages and assign grades.

| Average Marks | Grade |
|:---:|:---:|
| ≥ 90 | 🏆 **A+** |
| 80 – 89 | ⭐ **A** |
| 70 – 79 | ✅ **B** |
| 60 – 69 | 🔵 **C** |
| < 60 | ❌ **F** |

---

### 📚 Course Enrollment
Assign students to any of the available courses:

| # | Course |
|---|--------|
| 1 | 🐍 Python Programming |
| 2 | 🌳 Data Structures |
| 3 | 🤖 AI Fundamentals |
| 4 | 🗄️ Database Systems |

---

### 🗃️ Student Record Management
- View complete student profiles with marks and grades
- Search students instantly by USN
- Display enrolled courses per student

---

### 🏅 Rank List Generation
Automatically sort students by average marks and generate a ranked leaderboard — complete with top-scorer identification and performance comparisons.

---

### 💰 Fee Calculation
Transparent, formula-driven fee computation:

```
Total Fee = Tuition Fee + Laboratory Fee + Examination Fee
```

---

### 📁 File Handling
Persist your data across sessions:
- **Save** — writes student records to `student_records.txt`
- **Read** — retrieves and displays all previously stored records

---

### 🔍 Directory Scanner
Scan any folder path and list all files within it. Gracefully handles:
- `FileNotFoundError`
- `PermissionError`
- General exceptions

---

### 📊 Performance Analytics
Powered by **NumPy**, **Pandas**, and **Matplotlib**:

| Metric | Description |
|--------|-------------|
| 📈 Highest Average | Top-performing student score |
| 📉 Lowest Average | Area for academic support |
| 📐 Class Average | Overall cohort benchmark |
| 📊 Bar Chart | Visual performance comparison |

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|-----------|
| **Language** | Python 3.x |
| **Data Analysis** | NumPy, Pandas |
| **Visualization** | Matplotlib |
| **File System** | OS Module |
| **Core Concepts** | Functions, Lists, Dicts, File I/O, Exception Handling |

---

## 📂 Project Structure

```
Smart-Campus-Information-System/
│
├── 📄 main.py                  # Application entry point
├── 📋 student_records.txt      # Persistent data storage
├── 📘 README.md                # Project documentation
└── 📦 requirements.txt         # Python dependencies
```

---

## ⚙️ Installation

### Prerequisites
- Python 3.x installed on your system
- `pip` package manager

### Step-by-Step Setup

```bash
# 1️⃣ Clone the repository
git clone https://github.com/your-username/smart-campus-information-system.git

# 2️⃣ Navigate into the project directory
cd smart-campus-information-system

# 3️⃣ Install required dependencies
pip install numpy pandas matplotlib
```

---

## ▶️ Usage

```bash
python main.py
```

You'll be greeted with the main menu:

```
╔══════════════════════════════════════════════════╗
║       SMART CAMPUS INFORMATION SYSTEM            ║
╠══════════════════════════════════════════════════╣
║  1.  Student Registration                        ║
║  2.  Course Enrollment                           ║
║  3.  Display Student Records                     ║
║  4.  Search Student                              ║
║  5.  Sort Students (Rank List)                   ║
║  6.  Fee Calculation                             ║
║  7.  Save Records                                ║
║  8.  Read Records                                ║
║  9.  Directory Scanner                           ║
║  10. Performance Analytics                       ║
║  11. Exit                                        ║
╚══════════════════════════════════════════════════╝
```

---

## 📋 Sample Output

### Student Registration
```
Enter USN  : 1RV21CS001
Enter Name : Rahul

Enter Subject 1 Marks : 85
Enter Subject 2 Marks : 90
Enter Subject 3 Marks : 88

✅ Student Registered Successfully
   Grade Awarded : A
```

### Rank List
```
╔══════════════════════════════╗
║        RANK LIST             ║
╠══════════════════════════════╣
║  #1  Rahul     →  87.67      ║
║  #2  Priya     →  84.33      ║
║  #3  Arjun     →  79.00      ║
╚══════════════════════════════╝
```

### Performance Analytics
```
╔══════════════════════════════╗
║     PERFORMANCE ANALYTICS    ║
╠══════════════════════════════╣
║  📈 Highest Average : 92.5   ║
║  📉 Lowest Average  : 68.3   ║
║  📐 Class Average   : 81.2   ║
╚══════════════════════════════╝
```

---

## 🎯 Learning Outcomes

By exploring this project, you will gain hands-on experience with:

- ✅ Designing student information management systems
- ✅ Python fundamentals: functions, loops, and conditionals
- ✅ Working with lists and dictionaries for real-world data modeling
- ✅ Numerical computing with **NumPy**
- ✅ Tabular data analysis with **Pandas**
- ✅ Chart generation and data visualization with **Matplotlib**
- ✅ File I/O operations and safe exception handling

---

## 🔮 Future Roadmap

| Enhancement | Status |
|-------------|--------|
| 🖥️ GUI with Tkinter / PyQt | 🔜 Planned |
| 🗄️ SQLite / MySQL Integration | 🔜 Planned |
| 📅 Attendance Management Module | 🔜 Planned |
| 👩‍🏫 Faculty Management Module | 🔜 Planned |
| 🔐 Authentication & Login System | 🔜 Planned |
| 📄 PDF Report Generation | 🔜 Planned |
| 🌐 Web App with Flask / Django | 🔜 Planned |
| ☁️ Cloud Data Storage | 🔜 Planned |

---

<div align="center">

## 👨‍💻 About

**Smart Campus Information System** was developed as a mini project to demonstrate Python-based academic management and analytics in a structured, real-world context.

---

*Built with ❤️ using Python · Designed for learning · Open for contributions*

</div>
