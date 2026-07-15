# 🚀 MySQL DBMS – God Mode Revision ⚡

> **⚠️ Built this in the very last hour before submission.**
> I like to call it **"God Mode Revision"** because it covers almost everything I learned throughout my DBMS (MySQL) lab sessions in one repository. 😄

This repository contains all the SQL scripts, database schemas, queries, stored procedures, and screenshots completed during my **Database Management System (DBMS)** course for **B.E. in Information Technology**. It starts with the fundamentals of database creation and gradually progresses to advanced SQL concepts including joins, subqueries, stored procedures, user management, and role-based access control.

---

# 📚 Topics Covered

## 🟢 Lab 1 – Database & Table Fundamentals

This lab focused on understanding the basic structure of relational databases.

### Concepts Learned

* Creating databases
* Creating tables
* Defining columns and data types
* Primary Keys
* AUTO_INCREMENT
* UNIQUE constraints
* Inserting records
* Retrieving data using `SELECT`

### Practical Implementation

Created a **College** database containing a **Students** table with:

* Student ID
* First Name
* Last Name
* Address
* Email

and inserted sample student records to verify the table structure.

---

## 🟡SQL Queries, Relationships & Database Operations

These labs formed the core of the course by building a complete relational database system.

### Database Design

Three interconnected tables were created:

* **Students**
* **Courses**
* **Enrollment**

The **Enrollment** table acts as a bridge table that establishes a **many-to-many relationship** between students and courses using foreign keys.

---

## 🔍 Data Retrieval (SELECT Queries)

Learned different ways to retrieve and filter information from tables.

Covered:

* Selecting all records
* Selecting specific columns
* Filtering using `WHERE`
* Comparison operators (`>`, `<`, `=`)
* Pattern matching with `LIKE`
* Searching using wildcards (`%`)
* Sorting using `ORDER BY`
* Searching by exact values

---

## 🏗️ Table Modification (ALTER TABLE)

Learned how database structures evolve over time without recreating tables.

Performed operations like:

* Adding new columns
* Adding default values
* Changing column data types
* Renaming columns
* Dropping columns
* Adding CHECK constraints

---

## ✏️ Updating Existing Records (UPDATE)

Practiced modifying data already stored in tables.

Included:

* Updating a single field
* Updating multiple columns simultaneously
* Conditional updates
* Bulk updates
* Using SQL functions during updates
* Updating values through subqueries

---

## 🗑️ Removing Data (DELETE)

Learned different approaches for deleting information safely.

Covered:

* Deleting individual records
* Conditional deletion
* Deleting related records while maintaining referential integrity
* Clearing entire tables

---

## 📊 Aggregate Functions

Used SQL aggregate functions to analyze datasets.

Functions practiced:

* `COUNT()`
* `AVG()`
* `SUM()`
* `MAX()`
* `MIN()`

Applications included:

* Counting students
* Average student age
* Maximum course credits
* Youngest student
* Total course credit hours

---

## 📈 GROUP BY & HAVING

Learned how SQL groups records and performs calculations on each group.

Implemented:

* Student count per course
* Course count per student
* Filtering grouped results using `HAVING`

---

## 🔗 Joins & Relationships

One of the most important DBMS concepts covered.

Implemented:

### INNER JOIN

* Student with enrolled courses
* Student names with course names

### LEFT JOIN

* Courses with zero enrollments
* Students not enrolled in any course

### Multi-table Joins

Calculated:

* Total credit hours per student
* Active students in a specific course

These exercises demonstrated how relational databases connect multiple tables efficiently.

---

## 🧠 Subqueries

Learned how one SQL query can depend on the result of another.

Examples included:

* Students enrolled in the highest credit-hour course
* Courses with above-average enrollment
* Students older than the average age

This introduced nested SQL queries and advanced filtering techniques.

---

## ⚙️ Stored Procedures

Created reusable SQL procedures to automate common operations.

Implemented:

### GetStudentCourses

Returns all courses enrolled by a specific student.

### EnrollStudent

Automates the enrollment process by inserting records into the Enrollment table.

These labs introduced procedural programming inside MySQL.

---

## 🔄 Data Manipulation (DML)

Performed practical data manipulation tasks including:

* Updating course credit hours
* Managing enrollment data
* Executing stored procedures
* Modifying existing datasets

---

# 🔐 Lab 5 – Database Users & Privilege Management

This lab introduced database security from the administrator's perspective.

### Concepts Covered

* Creating users
* Dropping users
* Viewing existing users
* Granting permissions
* Revoking permissions
* Viewing granted privileges

Permissions practiced included:

* SELECT
* INSERT
* UPDATE
* DELETE
* Database-level access control

This demonstrated how MySQL manages authentication and user-specific privileges.

---

# 👥 Lab 07 – Roles & Role-Based Access Control (RBAC)

Instead of assigning permissions directly to every user, this lab introduced **Roles**, making privilege management more scalable.

### Topics Covered

* Creating roles
* Dropping roles
* Assigning roles to users
* Granting permissions to roles
* Revoking permissions from roles
* Viewing role grants
* Viewing assigned roles

This demonstrated the principle of **Role-Based Access Control (RBAC)** used in enterprise database systems.

---

# 🎯 SQL Concepts Practiced Throughout the Labs

* Database Creation
* Table Creation
* Primary Keys
* Foreign Keys
* Constraints
* AUTO_INCREMENT
* UNIQUE Constraints
* CHECK Constraints
* CRUD Operations
* SELECT Queries
* WHERE Clause
* ORDER BY
* LIKE Operator
* Aggregate Functions
* GROUP BY
* HAVING
* INNER JOIN
* LEFT JOIN
* Multi-table Joins
* Subqueries
* Stored Procedures
* Data Manipulation Language (DML)
* Data Definition Language (DDL)
* User Management
* Role-Based Access Control (RBAC)
* Privilege Management
* Referential Integrity

---

# 🎓 What I Learned

By completing these labs, I gained hands-on experience with:

* Designing relational databases
* Writing efficient SQL queries
* Managing and modifying database schemas
* Performing CRUD operations
* Working with relationships using joins
* Analyzing data through aggregate functions
* Writing nested queries
* Creating reusable stored procedures
* Managing database users and permissions
* Implementing Role-Based Access Control (RBAC)
* Understanding how relational databases are structured and administered in real-world applications

Overall, this repository represents my practical journey through the core concepts of **Database Management Systems (DBMS)** using **MySQL**, progressing from beginner-level SQL operations to database administration and security.
