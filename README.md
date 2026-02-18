# Library-Management-System - SQL Project

## Project Overview
This project is a Library Management System built using MySQL.
It focuses on designing a relational database and writing analytical queries to extract meaningful insights about library inventory, borrower activity, and branch performance.

The project demonstrates practical SQL skills required for Data Analyst and Database roles.

---
## PROBLEM:

Libraries often struggle to manage book inventory, borrower records, and branch operations efficiently due to manual processes and disconnected systems. This results in inaccurate stock tracking, delayed return monitoring, inefficient circulation management, and lack of data-driven decision-making.

## SOLUTION:

A centralized Library Management System is required to store, manage, and analyze data related to books, authors, publishers, borrowers, branches, and loans.

The system provides real-time visibility into inventory, improves loan tracking, and enables operational insights through SQL analysis.

## Objectives
- Design a structured and normalized relational database
- Maintain data integrity using Primary Keys and Foreign Keys
- Establish relationships between books, authors, branches, and borrowers
- Perform analytical queries on loans and inventory
- Extract business insights from transactional library data

## Tools & Technologies
- MySQL
- SQL

## Database Schema
The database consists of the following tables:

- **tbl_publisher** – Stores publisher details
- **tbl_book** – Stores book information (linked to publisher)
- **tbl_book_authors** – Maps books to authors (Many-to-Many relationship)
- **tbl_library_branch** – Contains branch information
- **tbl_book_copies** – Tracks number of copies per branch
- **tbl_borrower** – Stores borrower details
- **tbl_book_loans** – Tracks issued books and due dates

All tables are connected using Primary Keys and Foreign Keys to ensure referential integrity.

---

## Analysis Performed
This project answers key business questions such as:

- Number of copies of a book in a specific branch
- Total copies available across all branches
- Borrowers who currently have no books issued
- Books due on a specific date at a branch
- Total books loaned from each branch
- Borrowers who checked out more than 5 books
- Availability of books by a specific author (e.g., Stephen King) in a branch

---

## SQL Concepts Demonstrated
- Relational database design
- Database normalization
- CREATE TABLE and constraints
- PRIMARY KEY and FOREIGN KEY
- JOIN operations (INNER JOIN, LEFT JOIN)
- GROUP BY and HAVING
- Aggregate functions (COUNT, SUM)
- Date filtering
- Business-oriented SQL analysis

---

## Final Business Insights

- Identify high-performing and underutilized branches
- Detect frequent borrowers (power users)
- Analyze popular authors and demand trends
- Monitor due-date patterns and peak return periods
- Support inventory and procurement decisions

---

## 👤 Author
**Tharun Tej.K**
Email: [tharuntejkilaru@gmail.com](mailto:tharuntejkilaru@gmail.com)
