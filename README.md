# SQL_Task1_Library_DB

# 📘 SQL Developer Internship - Task 1

## 🚀 Objective
This project is part of the SQL Developer Internship. The goal is to design a database schema, implement it using SQL, and visualize it through an ER diagram.

## 📂 Domain: Library Management System
Entities considered:
- **Students**: Borrowers who issue books.
- **Authors**: Writers of books.
- **Books**: Collection of books in the library.
- **Borrow Records**: Tracks which student borrowed which book.

## 🗄️ Schema
- **students** (student_id, name, email, department)  
- **authors** (author_id, name)  
- **books** (book_id, title, isbn, published_year, author_id)  
- **borrow_records** (borrow_id, student_id, book_id, borrow_date, return_date)  

Relationships:
- One author → many books  
- One student → many borrow records  
- One book → many borrow records  

## 📜 Files Included
- `schema.sql` → SQL script to create the database and tables.  
- `ER_diagram.png` → Visual representation of the database schema.  
- `README.md` → Explanation of the project.  

## ⚙️ How to Run
1. Open MySQL Workbench (or pgAdmin / SQLiteStudio).  
2. Copy-paste the SQL code from `schema.sql`.  
3. Run the script to create the schema.  
4. Use `SELECT * FROM table_name;` to verify table creation.  

## 📚 Key Concepts Covered
- DDL commands (`CREATE DATABASE`, `CREATE TABLE`, `FOREIGN KEY`)  
- Primary Key & Foreign Key  
- Relationships in DBMS (1:M, M:N)  
- ER Diagram  

## ✅ Outcome
A well-
