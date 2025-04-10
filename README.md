# Bank Account Management System

## Project Overview

The **Bank Account Management System** is a SQL-based relational database project that simulates real-world banking operations. It allows customers to create accounts, perform transactions, and view reports. The system is designed to showcase the use of advanced SQL concepts including DDL, DML, subqueries, and various JOIN operations.

---

## Authors

- **Maryam Baizhigitova** – ERD design, DML, subqueries, and overall structure  
- **Moldir Kumarbek** – DDL operations, debugging, queries, and presentation  

---

## Entity-Relationship Diagram (ERD)

The ERD uses **Crow’s Foot Notation** and includes the following entities:

- `Bank`
- `Branches`
- `Departments`
- `Employees`
- `Products_Services`
- `Customer_Acquests`
- `Customers`
- `Accounts`
- `Transactions`
- `Customer_Types`
- `Account_Types`
- `Transaction_Types`

All entities are connected using appropriate foreign key constraints, ensuring referential integrity.

---

## Features

- Add and manage customers, employees, branches, and services
- Track transactions across various accounts
- Query specific bank details, customer types, and transaction history
- Use subqueries for deeper analytical queries
- Fully normalized database structure with extensive use of foreign keys

---

## Technologies Used

- SQL Server (Online Compiler and SQL Shell)
- Crow’s Foot Notation for ERD
- SQL language (DDL, DML, Subqueries, Aggregate Functions)

---

## SQL Operations

### DDL:
- `CREATE TABLE`
- `ALTER TABLE`
- Primary & Foreign Key Constraints

### DML:
- `INSERT INTO`
- `UPDATE`
- `DELETE`

### Queries:
- `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, `FULL OUTER JOIN`
- `MIN`, `MAX`, `SUM`, `AVG`, `COUNT`
- `AND`, `OR`, `ORDER BY`

### Subqueries:
- Single-row
- Multiple-row
- Multiple-column

---

## 📝 How to Run

1. Open an SQL Server environment (online compiler or local SQL Shell)
2. Copy and run the DDL statements to create all tables
3. Insert data using provided `INSERT INTO` statements
4. Test with queries and subqueries to retrieve relevant data
5. Modify or expand based on additional requirements

---

## Future Enhancements

- Build a user interface (web or desktop)
- Add authentication and role-based access
- Implement procedures and triggers for automation
- Real-time transaction logging and alerts

---

## Acknowledgment

This project was developed as part of the **Information and Communication Technologies Final Project** in Astana, 2020. It served as both a technical and collaborative learning experience.

---

## Contact

For questions or suggestions, feel free to reach out to:

- Maryam Baizhigitova
- Moldir Kumarbek

