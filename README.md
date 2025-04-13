# 🐬 Hands-on Lab: CREATE, ALTER, TRUNCATE, DROP in MySQL using phpMyAdmin

Welcome to this interactive lab experience focused on mastering basic SQL operations using **phpMyAdmin** on a **MySQL** database! 🚀 Whether you're a beginner or brushing up on SQL fundamentals, this lab will guide you through core SQL statements: `CREATE`, `ALTER`, `TRUNCATE`, and `DROP`.

---

## 🔧 Software Used

- **MySQL** – Relational Database Management System (RDBMS)
- **phpMyAdmin** – Web-based MySQL administration tool
- **IBM Skills Network Labs (SN Labs)** – Virtual Cloud IDE for lab exercises

---

## 🎯 Lab Objectives

By the end of this lab, you will be able to:

- ✅ Create a database using phpMyAdmin GUI  
- ✅ Create and modify tables using SQL statements  
- ✅ Insert and manipulate data  
- ✅ Alter table structure (add, delete, rename, modify columns)  
- ✅ Truncate tables to remove all data  
- ✅ Drop tables completely from the database  

---

## 📌 Tasks Overview

### 🗂️ Task 1: Create a Database

- Create a new database named `Mysql_Learners` using the GUI.

### 📝 Task 2a: CREATE Tables

Create the following tables using SQL:

```sql
CREATE TABLE PETSALE (
    ID INTEGER NOT NULL,
    PET CHAR(20),
    SALEPRICE DECIMAL(6,2),
    PROFIT DECIMAL(6,2),
    SALEDATE DATE
);

CREATE TABLE PET (
    ID INTEGER NOT NULL,
    ANIMAL VARCHAR(20),
    QUANTITY INTEGER
);
