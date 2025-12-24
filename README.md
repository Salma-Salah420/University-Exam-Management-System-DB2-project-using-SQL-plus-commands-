# University-Exam-Management-System-DB2-project-using-SQL-plus-commands-
![image](https://github.com/Salma-Salah420/University-Exam-Management-System-DB2-project-using-SQL-plus-commands-/blob/24fd937801f9bf0dbf7a4350837fc43a8559749d/download.webp)

Exam Management System (Using SQL*Plus):
==========================================

The Exam Management System is a database-driven system developed using Oracle SQL*Plus to manage and control all exam-related operations in an academic environment. The system is designed to ensure data integrity, security, and correctness while handling students, courses, exams, and results.

Using SQL*Plus commands, the system creates and manages database objects such as tables, constraints, views, sequences, triggers, and stored procedures to automate exam processes and enforce academic rules.

Key Features:
==============

Student Management
Stores student information such as ID, name, department, and academic status. Constraints ensure valid and consistent data entry.
==============

Course & Exam Management
Manages courses, exam schedules, and exam types (midterm, final, quiz). Primary and foreign keys maintain relationships between students, courses, and exams.
=================

Registration Control
Uses triggers to validate exam registration rules, such as:
===========================

Preventing suspended students from registering for exams

Ensuring course prerequisites are completed

Avoiding duplicate registrations

Grade & Result Handling
Stores exam results securely and applies rules to ensure grades fall within valid ranges using CHECK constraints and triggers.

Automation & Integrity

Sequences automatically generate unique IDs

Triggers enforce business rules before INSERT or UPDATE operations

Stored procedures simplify common tasks like adding exams or calculating final grades

==============================


Security & Access Control:
=============================
Implements roles and privileges using SQL*Plus to restrict access, ensuring only authorized users (e.g., admin, instructor) can perform specific operations.


=======================================

Technologies Used:
=====================

Oracle Database

SQL*Plus

SQL (DDL, DML, DCL)

PL/SQL (Triggers, Procedures, Functions)

================================================

Benefits:
===========

Ensures accurate and consistent exam data

Reduces manual errors through automation

Enforces academic policies at the database level

Secure and scalable for university-level usage
