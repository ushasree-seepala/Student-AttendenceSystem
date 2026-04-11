# Student Attendance Management System

## Project Description
Developing a Java-based console application to manage and track student attendance. The system currently supports core functionalities like adding students, marking attendance, and calculating attendance percentage. This is an ongoing project, with plans to enhance it into a full-stack application.

---

## Current Features

### 1. Student Management
- Add new students with roll number and name  
- Prevent duplicate entries using unique roll number  

### 2. Attendance Tracking
- Mark attendance as Present (P) or Absent (A)  
- Automatically updates total and attended classes  

### 3. Attendance Analysis
- Calculates attendance percentage  
- Displays warning if attendance is below 75%  
- Provides an estimate of safe bunk limit  

### 4. Data Storage
- Stores data in a file (attendance.txt)  
- Loads existing data at program start  
- Saves updated data on exit  

---

## Tech Stack
- Java  
- OOP Concepts (Classes, Objects, Encapsulation)  
- File Handling (BufferedReader, BufferedWriter)  
- Collections Framework (HashMap)  

---

## System Design

### Student Class
- Manages student details and attendance data  
- Key methods:
  - markAttendance()
  - getAttendancePercentage()
  - showStatus()

### Main System (AttendanceSystem)
- Uses HashMap to store student records  
- Provides menu-driven interaction  
- Handles file operations  

---

## Logic Flow
1. Load student data from file  
2. Display menu options  
3. Take user input  
4. Perform selected operation:
   - Check attendance  
   - Mark attendance  
   - Add student  
5. Update data in memory  
6. Save data before exiting  

---

## Core Logic
- Attendance % = (attendedClasses * 100.0) / totalClasses  
- If attendance < 75% → Warning message  
- Else → Estimate safe bunk limit  

---

## How to Run

1. Compile:
   javac AttendanceSystem.java  

2. Run:
   java AttendanceSystem  

---

## Future Enhancements
- Add user interface using HTML, CSS, and JavaScript  
- Integrate database (MySQL) instead of file storage  
- Add login system for admin and students  
- Convert into a full-stack web application  

---

## Limitations
- Console-based application  
- Uses file storage instead of database  
- No authentication system  

---

## Conclusion
This project demonstrates the use of Java OOP concepts, file handling, and collections to build a simple and functional attendance management system. It is currently being enhanced to improve usability and scalability.

Author Usha Sree Seepala
LinkedIn: Usha Sree Seepala
GitHub: ushasree-seepala
