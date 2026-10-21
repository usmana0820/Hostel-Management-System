# Hostel Management System

A C++ console-based application developed as an **Object-Oriented Programming (OOP)** project to simplify hostel administration. The system manages student records, mess services, guest expenses, laundry charges, security operations, staff salaries, and monthly student dues across four hostels.

## 📌 Project Overview

The system supports three boys' hostels and one girls' hostel, with separate management modules and file-based recordkeeping. It is designed around a central management class and specialized classes for hostel operations.

## ✨ Features

### 🏠 Hostel Management
- Manage three boys' hostels and one girls' hostel.
- Maintain separate records for each hostel.
- Support student registration and record management.
- Designed around a minimum of 200 residents per hostel.

### 👨‍🎓 Student Management
- Add, view, update, and delete student records.
- Store student names, roll numbers, and ID card numbers.
- Retrieve student dues using an ID card number.
- Manage student fines and monthly billing records.

### 🍽️ Mess Management
- Maintain separate mess records for all four hostels.
- Organize monthly menus and meal records.
- Track breakfast and dinner participation.
- Maintain records covering a 30-day period.

### 👥 Guest Management
- Record student guest details and guest meals.
- Maintain separate guest records for each hostel.
- Calculate guest meal expenses using a dedicated total-calculation function.

### 👕 Clothes Management
- Track laundry and ironing services.
- Washing charge: **Rs. 12 per piece**
- Ironing charge: **Rs. 5 per piece**
- Calculate the hostel's 15% share of clothing-service revenue.

### 🛡️ Security Management
- Maintain guest ID card records.
- Organize guard shifts and control-room staffing.
- Record extracurricular activities, including weekend trips and monthly bonfires.
- Track lost and found items and applicable fines.

### 💰 Salary Management
Manage the specified monthly salaries:

| Staff Position | Monthly Salary |
|---|---:|
| Manager | Rs. 25,000 |
| Guard | Rs. 15,000 |
| Cook | Rs. 15,000 |
| Sweeper | Rs. 10,000 |
| Serving Boy | Rs. 5,000 |

### 📊 Accounts and Billing
- Calculate student expenses at the end of the month.
- Combine applicable mess charges, guest meal expenses, and fines.
- Maintain salary and hostel-profit records.
- Calculate and display outstanding dues for a student using their ID card number.

## 🛠️ Technologies Used

- **C++** — Core application logic
- **Object-Oriented Programming** — Classes, subclasses, and modular management
- **File Handling** — Persistent storage of student, mess, guest, clothing, security, and financial records
- **Console Interface** — Menu-driven user interaction

## 📋 Application Menu

### Main Menu

```text
========================================
       HOSTEL MANAGEMENT SYSTEM
========================================
Press 1 for Boy Hostel 1
Press 2 for Boy Hostel 2
Press 3 for Boy Hostel 3
Press 4 for Girls Hostel
Press 5 to Exit
========================================
```

### Student Management Menu

```text
========================================
       STUDENT MANAGEMENT SYSTEM
========================================
Press 1 to Add Student
Press 2 to View Students
Press 3 to Update Student
Press 4 to Delete Student
Press 5 to Manage Fines
Press 9 to Return to Previous Menu
========================================
```

## 🚀 Installation and Execution

### Prerequisites

- A C++ compiler, such as GCC or MinGW
- A terminal or command prompt

### 1. Clone the Repository

```bash
git clone https://github.com/usmana0820/Hostel-Management-System.git
```

### 2. Navigate to the Project Directory

```bash
cd Hostel-Management-System
```

### 3. Compile the Program

The main source file in this repository is named `Hostel management system.cpp`. Compile it using:

```bash
g++ "Hostel management system.cpp" -o hostel_management_system
```

### 4. Run the Application

**Windows:**

```bash
hostel_management_system.exe
```

**Linux/macOS:**

```bash
./hostel_management_system
```

## 📁 Repository Structure

```text
Hostel-Management-System/
├── Hostel management system.cpp
├── Question with Output.pdf
├── LICENSE
└── README.md
```

## 🎯 Learning Objectives

This project demonstrates practical applications of:

- Object-oriented programming and class relationships
- File handling and persistent data storage
- Menu-driven console application development
- Financial calculations and record management
- Modular software design and problem-solving

## 🔮 Potential Improvements

- Add input validation and duplicate student-ID checks.
- Introduce backups and safer file-update operations.
- Improve monthly financial reports and hostel-wise profit summaries.
- Add automated tests for billing, salaries, and guest expenses.
- Implement authentication and role-based access for administrators.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📬 Contact

- **GitHub:** [@usmana0820](https://github.com/usmana0820)
- **Email:** usmanazulfiqar20@gmail.com

## 👩‍💻 Developer

**Usmana Zulfiqar**

C++ Development | Object-Oriented Programming | File Handling

---

*Developed as an academic project to explore object-oriented programming through practical hostel administration and financial management.*
