# Student Management System

## 📌 Project Description

The **Student Management System** is a simple Python-based application used to manage student records.

The program stores student information such as **Roll Number, Name, and Marks** in a CSV file. It allows users to add, search, display, and delete student records. All changes are saved permanently in the CSV file.

## ✨ Features

* Add new student records
* Display all student records
* Search for a student using Roll Number
* Delete a student record
* Automatically creates the CSV file
* Saves all changes permanently
* Prevents duplicate Roll Numbers

## 🛠️ Technologies Used

* **Python**
* **CSV module**
* **File Handling**
* **Functions**
* **Loops and Conditional Statements**

## 📂 Project Structure

```text
Student-Management-System/
│
├── student_management.py
├── students.csv
└── README.md
```

## ▶️ How to Run

### 1. Install Python

Make sure Python is installed on your computer.

### 2. Download or Clone the Project

Download the project files to your computer.

### 3. Run the Program

Open the project folder in a terminal or command prompt and run:

```bash
python student_management.py
```

## 📋 Menu Options

When the program starts, the following menu is displayed:

```text
========== STUDENT MANAGEMENT SYSTEM ==========
1. Add Student
2. Display Students
3. Search Student
4. Delete Student
5. Exit
```

### 1. Add Student

Enter the student's:

* Roll Number
* Name
* Marks

The information is automatically saved in `students.csv`.

### 2. Display Students

Displays all student records stored in the CSV file.

### 3. Search Student

Enter a Roll Number to find a particular student's details.

### 4. Delete Student

Enter a Roll Number to remove a student from the records.

### 5. Exit

Closes the Student Management System.

## 💾 Data Storage

Student information is stored in a CSV file named:

```text
students.csv
```

Example:

```text
Roll Number,Name,Marks
101,Anurag,85
102,Rahul,78
103,Priya,92
```

The data remains saved even after the program is closed.

## 🎯 Objective

The objective of this project is to demonstrate the use of **Python programming, CSV file handling, functions, and basic CRUD operations** to create a simple student record management system.

## 👨‍💻 Author

**Anurag Kumar Rana**
