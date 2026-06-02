# Hospital Management System – SQL Project

## Project Overview
The Hospital Management System is a database project developed using SQL to manage hospital operations efficiently. This system stores and manages information related to doctors, patients, appointments, prescriptions, and billing records.

The project demonstrates database design, table relationships, data handling, and report generation using SQL queries.

---

## Features

* Manage doctor information
* Store patient details
* Schedule and track appointments
* Maintain prescription records
* Generate and manage billing details
* Produce reports using SQL queries

---

## Database Tables

### Doctors

Stores doctor information such as:

* Doctor ID
* Doctor Name
* Specialization
* Phone Number
* Experience

### Patients

Stores patient details including:

* Patient ID
* Name
* Age
* Gender
* Contact Number
* Address

### Appointments

Manages appointment scheduling between doctors and patients:

* Appointment ID
* Patient ID
* Doctor ID
* Appointment Date
* Appointment Time
* Status

### Prescriptions

Stores medicine and treatment details:

* Prescription ID
* Appointment ID
* Medicine
* Dosage
* Notes

### Billing

Handles payment and bill records:

* Bill ID
* Patient ID
* Amount
* Payment Status
* Bill Date

---

## SQL Concepts Used

### Database Creation

The project begins by creating and selecting a database using:

* CREATE DATABASE
* USE

### Table Creation

Tables are created using:

* CREATE TABLE
* Primary Key
* Foreign Key

These relationships ensure data integrity and proper connection between tables.

### Data Insertion

Data is inserted using:

* INSERT INTO

This allows storing doctor, patient, appointment, and billing records.

### Data Retrieval

Information is retrieved using:

* SELECT
* WHERE
* ORDER BY

These queries help filter and display required records.

### JOIN Operations

JOIN queries combine data from multiple tables.

Examples:

* Patient and Doctor appointment details
* Billing linked with patient records

This helps generate meaningful reports.

### Aggregate Functions

Used for data analysis:

* COUNT()
* SUM()
* AVG()

Examples:

* Total patients
* Total revenue
* Average patient age

### GROUP BY and HAVING

Used to organize and filter grouped data.

Examples:

* Patients handled by each doctor
* Doctors with high appointment counts

### Views

Views simplify complex queries by storing reusable query logic.

### Stored Procedures

Stored procedures help automate reusable database operations.

Example:

* Retrieve patient details using Patient ID

### Functions

Functions are used to return calculated values.

Example:

* GST calculation for bills

### Triggers

Triggers perform automatic actions inside the database.

Example:

* Automatically inserting bill date during billing entry

---

## Learning Outcomes

This project helped in understanding:

* Relational database design
* Table relationships
* SQL query writing
* Report generation
* Data integrity using keys
* Database automation using procedures and triggers

---

## Technologies Used

* MySQL
* SQL
* MySQL Workbench / XAMPP

---

## Conclusion

The Hospital Management System demonstrates how SQL can be used to design and manage a real-world healthcare database system. It provides practical experience in database development and helps strengthen SQL concepts for academic and interview preparation.
