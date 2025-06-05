# 🛒 Shopping Management System – DBMS Project

This is a Database Management System (DBMS) project developed as part of the UCS310 course. The project models the backend structure of an e-commerce shopping platform using **Oracle SQL** and **PL/SQL**. It focuses purely on the **relational database design** and backend logic, showcasing how data is organized, queried, and maintained in a structured shopping system.

## 📌 Project Overview

The **Shopping Management System** is designed to simulate the backend database for a retail e-commerce environment. It handles data for:

- Customers & their contact details
- Sellers & product listings
- Product categories
- Orders & detailed order records
- Payments & transactions
- Shipment tracking

The database schema has been normalized to **Third Normal Form (3NF)** to ensure efficiency and eliminate data redundancy.

## 🧱 Database Design

- **ER Diagram**: Models 8 key entities and their relationships
- **Normalization**: All tables are normalized to 3NF
- **Tables**: Customers, Sellers, Products, Categories, Orders, Order_Details, Payments, Shipments
- **Relationships**:
  - One-to-Many: Customers → Orders, Sellers → Products, Categories → Products
  - One-to-One: Orders → Shipments, Orders → Payments
  - Many-to-One: Order_Details → Products

## 🛠️ Technologies Used

- **Oracle SQL** – Data definition and manipulation
- **PL/SQL** – Stored procedures, triggers, cursors
- **ER Modelling** – Conceptual database design
- **3NF Normalization** – Ensures data integrity and efficiency

## 📂 Project Contents

- 📄 ER Diagram and ER-to-Relational Mapping  
- 🔄 SQL Scripts for Table Creation  
- 🧮 Normalization Justification  
- ⚙️ PL/SQL Triggers, Cursors, and Procedures  
- 📊 Joins and Subqueries with Sample Outputs  
- 📌 Final Queries and Results  

## 🚀 Highlights

- Accurate schema mapping with real-world retail logic
- Use of composite and foreign keys for relational integrity
- Simulated data insertions and output queries
- Sample business logic implementation via PL/SQL triggers

## 👩‍💻 Contributors
 
- Gursharen Kaur Suri  
- Harshleen Kaur 
- Dishavpreet Kaur  
- Karandeep Singh Bhasin  



> **Note**: This project focuses only on backend database design. No frontend or user interface is included.  
> Future enhancements could include a frontend layer, role-based access, and analytics features.

