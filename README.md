# 🎓 EduManage – Complete School Management System

<p align="center">

![PHP](https://img.shields.io/badge/PHP-5.6-777BB4?style=for-the-badge&logo=php)
![CodeIgniter](https://img.shields.io/badge/CodeIgniter-3-DD4814?style=for-the-badge&logo=codeigniter)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql)
![Bootstrap](https://img.shields.io/badge/Bootstrap-Responsive-7952B3?style=for-the-badge&logo=bootstrap)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript)
![License](https://img.shields.io/badge/License-Portfolio-blue?style=for-the-badge)

</p>

---

# 📚 Overview

**EduManage** is a modern and comprehensive **School Management System (SMS)** developed to digitize academic and administrative operations for schools, colleges, and educational institutions.

The system provides dedicated portals for **Administrators, Teachers, Students, and Parents**, enabling efficient management of academic sessions, classes, attendance, examinations, fee collection, communication, and institutional records from a centralized platform.

Developed using **PHP 5.6**, **CodeIgniter**, **MySQL**, **Bootstrap**, and **JavaScript**, EduManage delivers a secure, scalable, and responsive educational management solution.

---

# 📅 Project Information

| Item | Details |
|------|----------|
| **Project Name** | EduManage |
| **Duration** | June 2021 – March 2022 |
| **Category** | School Management System |
| **Architecture** | Multi-Portal Web Application |
| **Backend** | PHP 5.6 + CodeIgniter |
| **Frontend** | Bootstrap, HTML5, CSS3, JavaScript, jQuery |
| **Database** | MySQL |

---

# 🏗 System Architecture

```text
                         +----------------------+
                         |      Administrator   |
                         +----------+-----------+
                                    |
      --------------------------------------------------------
      |                     |                    |            |
      ▼                     ▼                    ▼            ▼
 Teachers              Students             Parents     Academic Staff
      |                     |                    |
      --------------------------------------------------------
                          |
               School Management System
                 (CodeIgniter Backend)
                          |
 ---------------------------------------------------------------
 |         |           |           |           |               |
 ▼         ▼           ▼           ▼           ▼               ▼
Academic Attendance Examination Fee Mgmt Communication Reports
Management Tracking     System      & Billing   & Noticeboard
                          |
                          ▼
                    MySQL Database
```

---

# 👥 User Portals

## 👨‍💼 Administrator

- Dashboard
- Academic Session Management
- Class & Section Management
- Student Management
- Teacher Management
- Parent Management
- Subject Management
- Fee Collection
- Examination Management
- Attendance Reports
- Library Management
- Transportation Management
- Dormitory Management
- Noticeboard
- Messaging System
- Reports
- System Settings

---

## 👨‍🏫 Teacher

- Dashboard
- Student Attendance
- Examination Marks Entry
- Class Routine
- Student Information
- Messaging
- Noticeboard
- Profile Management

---

## 👨‍🎓 Student

- Dashboard
- Attendance Reports
- Examination Results
- GPA & Mark Sheets
- Fee Status
- Class Routine
- Messages
- Notices
- Profile Information

---

## 👨‍👩‍👧 Parent

- Dashboard
- Child Academic Progress
- Attendance Reports
- Examination Results
- Fee Payment Status
- Teacher Communication
- School Notices
- Student Monitoring

---

# 🚀 Core Modules

## 📖 Academic Management

- Academic Sessions
- Class Management
- Section Management
- Subject Management
- Teacher Assignment
- Student Enrollment
- Class Routine Scheduling

---

## 👨‍🎓 Student Management

- Student Registration
- Student Profiles
- Enrollment History
- Academic Records
- Parent Mapping

---

## 👨‍🏫 Teacher Management

- Teacher Profiles
- Subject Assignment
- Class Assignment
- Teacher Information

---

## 📅 Attendance Management

- Daily Attendance
- Class-wise Attendance
- Section-wise Attendance
- Attendance Reports
- Student Attendance History
- Absence Monitoring

---

## 📝 Examination Management

- Examination Terms
- Subject Marks
- Grade Management
- GPA Calculation
- Mark Sheet Generation
- Printable Results

---

## 💰 Fee Management

- Fee Collection
- Student Invoices
- Payment Tracking
- Payment Status
- Financial Reports

---

## 📚 Library Management

- Library Books
- Book Records
- Student Library Information

---

## 🚌 Transportation

- Vehicle Information
- Student Transport Records
- Route Management

---

## 🏠 Dormitory Management

- Dormitory Details
- Room Allocation
- Student Accommodation Records

---

## 💬 Communication System

- Internal Messaging
- Seen / Unseen Messages
- Message History
- Noticeboard
- School Announcements

---

## ⚙ System Configuration

- Academic Sessions
- Grade Configuration
- Fee Structure
- General Settings
- User Profiles
- Permissions

---

# 🔐 User Roles

- Administrator
- Teacher
- Student
- Parent

Every user is authenticated through a secure **Role-Based Access Control (RBAC)** system with permission-based access.

---

# 🛠 Technology Stack

## Backend

- PHP 5.6
- CodeIgniter Framework

## Frontend

- Bootstrap
- HTML5
- CSS3
- JavaScript
- jQuery

## Database

- MySQL

---

# 🗄 Database Structure

The system manages information for:

- Users
- Students
- Teachers
- Parents
- Academic Sessions
- Classes
- Sections
- Subjects
- Attendance
- Examination Terms
- Marks
- Grades
- Payments
- Invoices
- Library Books
- Transport
- Dormitories
- Messages
- Noticeboard

---

# 📊 Academic Workflow

```text
Student Registration
        │
        ▼
Class & Section Assignment
        │
        ▼
Subject Enrollment
        │
        ▼
Daily Attendance
        │
        ▼
Class Routine
        │
        ▼
Examinations
        │
        ▼
Marks Entry
        │
        ▼
Automatic GPA Calculation
        │
        ▼
Mark Sheet Generation
        │
        ▼
Fee Collection
        │
        ▼
Invoice Generation
        │
        ▼
Parent Monitoring
```

---

# 📂 Project Structure

```text
application/
│
├── controllers/
├── models/
├── views/
├── libraries/
├── helpers/
├── config/
│
assets/
├── css/
├── js/
├── images/
│
uploads/
│
system/
│
index.php
```

---

# ⚡ Technical Highlights

- MVC Architecture (CodeIgniter)
- Modular Codebase
- Responsive Bootstrap UI
- Role-Based Authentication
- Student Attendance Tracking
- GPA Automation
- Examination Management
- Invoice Generation
- Fee Collection
- Internal Messaging
- Noticeboard System
- Reporting Module
- Session Management

---

# 📱 Responsive Design

Optimized for:

- 💻 Desktop
- 🖥 Laptop
- 📱 Mobile
- 📟 Tablet

---

# 🔒 Security Features

- Secure Login Authentication
- Session Management
- Role-Based Authorization
- Password Protection
- Permission Management
- Input Validation
- SQL Injection Protection (CodeIgniter Query Builder)

---

# 🎯 Project Highlights

- Complete Multi-Portal School Management System
- End-to-End Academic Administration
- Student Attendance Monitoring
- Examination & GPA Automation
- Fee Collection & Invoice Management
- Internal Communication Platform
- Library & Transportation Modules
- Dormitory Management
- Responsive Bootstrap Interface
- Secure Role-Based Authentication
- Modular MVC Architecture
- Scalable MySQL Database

---

# 📸 Major Modules

- Admin Dashboard
- Teacher Dashboard
- Student Dashboard
- Parent Dashboard
- Academic Sessions
- Student Management
- Teacher Management
- Attendance
- Examinations
- GPA & Grade Management
- Fee Collection
- Library
- Transportation
- Dormitories
- Reports
- Messaging
- Noticeboard
- System Settings

---

# 👨‍💻 Built With

- PHP 5.6
- CodeIgniter
- MySQL
- Bootstrap
- HTML5
- CSS3
- JavaScript
- jQuery

---

# 📄 License

This project is provided for **portfolio and educational demonstration purposes only**. Commercial use, redistribution, or resale requires permission from the project owner.

---

# ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub.

---

## 📬 Contact

For collaboration, customization, or enterprise solutions, feel free to connect.

**Developer:** Afrasiab Ahmad
