# 🏋️ Gym Membership Management System

## 📌 Project Overview

The **Gym Membership Management System** is a database management project developed using **Oracle SQL and PL/SQL**. It is designed to manage gym members, membership plans, trainers, payments, and attendance records efficiently.

The project demonstrates database concepts such as table creation, relationships, stored procedures, functions, triggers, cursors, exception handling, and reporting queries.

## 🎯 Objectives

- Manage gym member registration and details.
- Maintain membership plans and membership records.
- Store and validate gym payment transactions.
- Track member attendance.
- Manage trainer information.
- Calculate total payments made by a member.
- Generate reports for membership status, attendance, and monthly revenue.
- Demonstrate practical implementation of Oracle PL/SQL concepts.

## ✨ Features

- **Member Management:** Store and retrieve gym member information.
- **Membership Plans:** Maintain available membership plans and their details.
- **Trainer Management:** Store trainer information.
- **Payment Management:** Record payments and validate payment details.
- **Membership Renewal:** Renew existing gym memberships.
- **Attendance Tracking:** Maintain attendance records.
- **Stored Procedures:** Register members, record payments, and renew memberships.
- **PL/SQL Function:** Calculate the total paid amount for a particular member.
- **Database Trigger:** Validate payment amounts and standardize payment methods and statuses.
- **Cursor Handling:** Retrieve and process records using explicit cursors.
- **Exception Handling:** Handle errors such as missing member records.
- **Reports:** Generate membership, payment, attendance, and revenue reports.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Oracle SQL | Database creation and data management |
| PL/SQL | Procedures, functions, triggers, and program logic |
| DBMS_OUTPUT | Displaying messages and report results |
| OneCompiler / Oracle-compatible environment | Writing and testing SQL/PLSQL code |

## 🗄️ Database Tables

The project contains the following main tables:

| Table Name | Description |
|---|---|
| `GYM_MEMBERS` | Stores gym member details |
| `MEMBERSHIP_PLANS` | Stores membership plan information |
| `GYM_MEMBERSHIPS` | Maintains member membership records |
| `GYM_TRAINERS` | Stores trainer details |
| `GYM_PAYMENTS` | Records payment transactions |
| `GYM_ATTENDANCE` | Stores attendance records |

These tables are used to organize gym data and maintain relationships between members, memberships, plans, trainers, payments, and attendance.

## ⚙️ PL/SQL Concepts Implemented

### 1. Stored Procedures
- `REGISTER_GYM_MEMBER` — registers a new gym member.
- `RECORD_GYM_PAYMENT` — records a gym payment.
- `RENEW_GYM_MEMBERSHIP` — renews an existing membership.

### 2. Function
- `GET_TOTAL_PAYMENTS` — calculates the total amount of successful/paid transactions for a specified member, according to the project's payment-status logic.

### 3. Trigger
- `TRG_VALIDATE_GYM_PAYMENT` — validates payment amounts and normalizes payment methods and statuses before payment records are inserted or updated.

### 4. Cursor
Uses an explicit cursor to retrieve and process database records.

### 5. Exception Handling
Handles database errors, including cases where a requested member record is not found.

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Open an Oracle-compatible SQL/PLSQL environment, such as an appropriately configured Oracle worksheet.
3. Open the project's `.sql` file.
4. Execute the table creation statements first.
5. Execute the sample data insertion block.
6. Create the stored procedures, function, and trigger.
7. Run the PL/SQL test blocks.
8. Execute the reporting blocks to view the results.

**Important:** Run the project in a fresh schema for the easiest setup. The test blocks may insert additional sample records if executed more than once.

### Viewing Output

If your SQL environment supports `DBMS_OUTPUT`, enable it to view messages printed by PL/SQL blocks. Some online compilers may require you to execute statements in separate sections or blocks.

**Note:** Oracle PL/SQL syntax is used in this project. It is not intended to run unchanged in MySQL.

## 📊 Reports Included

The project includes queries or reporting blocks for:

- Gym member details
- Membership plan details
- Trainer information
- Payment records with member information
- Attendance records
- Membership status
- Monthly revenue
- Total attendance
- Total paid amount per member
- Verification of database objects

## 📂 Project Structure

```text
Gym-Membership-Management-System/
│
├── Gym_Membership_Management_PL_SQL.sql
├── README.md
└── Screenshots/
    └── Add project screenshots here
```

*Update the SQL filename in this structure if your uploaded file uses a different name.*

## 🎓 Academic Project Information

- **Project Title:** Gym Membership Management System
- **Student Name:** Mausam Chaturvedi
- **UID:** 26MCA20182
- **Course:** Master of Computer Applications (MCA)
- **Semester:** First Semester
- **Institution:** Chandigarh University
- **Academic Session:** 2026–27
- **Project Guide:** Ms. Ashima Sood

## 🔮 Future Enhancements

- Create a web-based interface for gym administrators.
- Add automated membership expiry notifications.
- Implement role-based access for administrators, trainers, and members.
- Generate printable payment receipts.
- Add dashboards for revenue and membership statistics.
- Integrate online payment processing.

## 📚 Learning Outcomes

This project provides practical experience with relational database design, SQL queries, PL/SQL programming, stored procedures, functions, triggers, cursors, exception handling, and database reporting.

## 👨‍💻 Author

**Mausam Chaturvedi**  
MCA Student | Chandigarh University

## 📄 License

This project was developed for educational and academic purposes. A license can be added if you intend to distribute or reuse the project publicly.
