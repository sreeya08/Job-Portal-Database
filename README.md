# Job Portal Database Management System

## 📌 Project Overview

The Job Portal Database Management System is a MySQL-based project designed to manage the recruitment process between companies and job seekers. It allows companies to post jobs, candidates to apply for positions, and recruiters to track applications and interview results.

This project demonstrates the use of relational database concepts including primary keys, foreign keys, relationships, and SQL queries.

---

## 🚀 Features

- Manage candidate information
- Store company details
- Post job openings
- Maintain skill records
- Track job applications
- Record interview schedules and results
- Generate applicant and hiring reports

---

## 🛠️ Technologies Used

- MySQL
- SQL (DDL, DML)

---

## 📂 Database Name

```
JobPortalDB
```

---

## 📋 Database Tables

| Table Name | Description |
|------------|-------------|
| Candidates | Stores candidate details |
| Companies | Stores company information |
| Jobs | Stores job openings |
| Skills | Stores skill information |
| Applications | Stores candidate job applications |
| Interviews | Stores interview details and results |

---

## 🔗 Database Relationships

- One Company ➜ Many Jobs
- One Candidate ➜ Many Applications
- One Job ➜ Many Applications
- One Application ➜ One Interview

---

## 📊 Sample Data

The database contains sample records for:

- 20 Candidates
- 20 Companies
- 20 Jobs
- 20 Skills
- 20 Applications
- 20 Interviews

---

## 📁 Project Structure

```
JobPortalDB
│
├── CREATE DATABASE
├── Candidates Table
├── Companies Table
├── Jobs Table
├── Skills Table
├── Applications Table
├── Interviews Table
└── Sample Data (INSERT Statements)
```

---

## 📈 Expected Outcome

- Applicant Reports
- Hiring Statistics
- Interview Tracking
- Company-wise Job Listings
- Candidate Application Status

---

## 📌 SQL Concepts Used

- CREATE DATABASE
- CREATE TABLE
- PRIMARY KEY
- FOREIGN KEY
- INSERT INTO
- Data Relationships

---

## ▶️ How to Run

1. Install MySQL Server.
2. Open MySQL Workbench or any SQL editor.
3. Create a new SQL script.
4. Copy and paste the SQL code.
5. Execute the script.
6. The database and all tables will be created with sample data.

---

## 📸 Sample Queries

```sql
-- Display all candidates
SELECT * FROM Candidates;

-- Display all companies
SELECT * FROM Companies;

-- Display all jobs
SELECT * FROM Jobs;

-- Display all applications
SELECT * FROM Applications;

-- Display interview results
SELECT * FROM Interviews;
```

---

## 🎯 Learning Outcomes

- Database Design
- Table Relationships
- SQL Commands
- Data Management
- Recruitment System Database Design

---

## 👩‍💻 Author

**Sreeya Malineni**

GitHub: https://github.com/your-username

---

## ⭐ If you found this project useful, consider giving it a star!
