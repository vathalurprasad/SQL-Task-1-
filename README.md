# SQL-Task-1-
#  Library Management Database Project

This project presents a well-structured relational database schema for managing a library system. The goal is to normalize book-related data and demonstrate SQL database design principles such as entity relationships, primary keys, and foreign key constraints.

---

##  Domain: Library Management

The domain focuses on maintaining records of books, their authors, publishers, categories, and availability in a library setting. This project models realistic data and relationships between entities in the library.

---

##  Database Design Objectives

- Choose a domain:  Library
- Identify entities and relationships
- Create normalized SQL tables using `CREATE TABLE`
- Define **Primary** and **Foreign Keys**
- Populate with sample data (30 books)
- Support query operations for future reporting or application development

---

##  Entities

1. **Books**
2. **Authors**
3. **Publishers**
4. **Categories**

---

##  Relationships

- Each book has one **Author**
- Each book has one **Publisher**
- Each book belongs to one **Category**
- Foreign keys link `Books` to `Authors`, `Publishers`, and `Categories`

---

##  Features of the Schema

- Proper normalization to avoid data redundancy
- Use of foreign keys for relational integrity
- Use of `SMALLINT` for `YearPublished` to support historic data
- Unique constraints on `ISBN`, `AuthorName`, and `PublisherName`
- Supports scalability (adding more books, authors, categories)

---

##  Sample Data

The project includes:
- 30 well-known books across genres like Fiction, Fantasy, Dystopian, Classic, etc.
- Authors, publishers, and categories stored as independent entities

---

##  Future Enhancements

- Add support for borrowers and loan records
- Build search/filter functionality using SQL queries
- Connect the database to a frontend web app for a complete library management system

---

##  Technologies Used

- **MySQL / SQL Workbench** for database creation and data insertion
- **SQL** for defining schema, constraints, and relationships

---

##  Outcome

A fully normalized, clean, and expandable **Library Management Database Schema** ready for use in applications, data analysis, or academic projects.

---

##  Author


