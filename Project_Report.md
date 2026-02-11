# Student Result & Academic Management System (SRAMS)

A C++ console-based academic management application designed to manage student records, faculty operations, marks entry, result processing, and CGPA calculation using Object-Oriented Programming and file handling.

---

## 📌 Project Overview

Student Result & Academic Management System (SRAMS) automates semester result processing by providing three separate panels:

- **Admin**
- **Faculty**
- **Student**

The system stores data in text files and calculates CGPA automatically based on subject credits and marks.

---

## 🎯 Objectives

- Manage student and faculty information
- Allow faculty to enter marks securely
- Automatically calculate total marks and CGPA
- Enable students to view routine and CGPA
- Apply OOP and file handling in a real-world project

---

## ✨ Features

### Admin Panel
- Add student information
- Add faculty information
- Calculate total marks
- Generate CGPA
- Fix student names
- Copy files

### Faculty Panel
- Set password
- Enter marks for courses

### Student Panel
- View personal details
- Edit information
- View class routine
- View CGPA result

---

## 🛠 Tools & Technologies

- Language: C++
- IDE: CodeBlocks / Dev-C++ / VS Code
- Compiler: GCC / MinGW

Concepts Used:
- Object-Oriented Programming
- File Handling
- STL (map, vector)
- Structures

---

## 📁 File Structure

- `Student.txt` – Student ID and Name  
- `Faculty.txt` – Faculty information  
- `Password.txt` – Faculty passwords  
- `CSE-111.txt`, `CSE-112.txt`, etc. – Subject marks  
- `Results.txt` – Total marks  
- `CGPA_SecondSemester.txt` – CGPA results  

---

## 📐 CGPA Formula

CGPA = Total (Grade Point × Credit) / Total Credits

---

## ⚠ Limitations

- No graphical user interface (GUI)
- Student login without password
- Data stored in plain text files
- Limited input validation

---

## 🚀 Future Improvements

- Add password-based student login
- Implement GUI
- Replace text files with database
- Improve security
- Show individual student result

---

## ▶ How to Run

1. Open the project in CodeBlocks / Dev-C++ / VS Code
2. Compile using GCC / MinGW
3. Run `main.cpp`
4. Follow on-screen menu instructions

---

## 📄 License

This project is for educational purposes.

---

## 👨‍💻 Developed By

Argho Ghosh  
Student of CSE, BUBT
