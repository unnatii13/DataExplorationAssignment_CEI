# ShopEase E-Commerce Sales Database

## Celebal Technologies – Summer Internship 2026

### Week 2 SQL Assignment

---

## Project Overview

This project was completed as part of the **Celebal Technologies Summer Internship 2026 – Week 2 Assignment**.

The objective of this assignment is to design and query a relational database for an e-commerce platform named **ShopEase**. The database stores customer, product, order, and order item information. Various SQL queries were written to analyze sales, customer behavior, and product performance.

---

## Tools Used

* PostgreSQL
* pgAdmin 4
* Git & GitHub

---

## Database Schema

The database consists of the following four tables:

* **customers**
* **products**
* **orders**
* **order_items**

### Relationships

* One customer can place many orders.
* One order can contain many order items.
* One product can appear in many order items.

---

## Features Implemented

### Section A – SQL Basics

* SELECT statements
* Constraints
* Primary Keys
* UNIQUE constraints
* CHECK constraints

### Section B – Filtering & Optimization

* WHERE clause
* BETWEEN
* DISTINCT
* Indexes
* Query optimization (SARGable queries)

### Section C – Aggregation

* COUNT()
* SUM()
* AVG()
* MIN()
* MAX()
* GROUP BY
* HAVING

### Section D – Joins & Relationships

* INNER JOIN
* LEFT JOIN
* RIGHT JOIN (Explanation)
* FULL OUTER JOIN (Explanation)
* Foreign Keys

### Section E – Advanced SQL

* CASE statement
* Aggregate CASE
* ACID properties
* SQL Transactions
* COMMIT and ROLLBACK

---

## Project Structure

```
Celebal_SQL_Task2_Week2/
│
├── solution.sql
├── README.md
├── screenshots/
│   ├── database.png
│   ├── tables.png
│   ├── insert_data.png
│   ├── q1.png
│   ├── q7.png
│   ├── q14.png
│   ├── q19.png
│   └── q24.png
└── Assignment.pdf (Optional)
```

---

## How to Run the Project

1. Install PostgreSQL and pgAdmin 4.
2. Create a database named **shopease**.
3. Open the Query Tool in pgAdmin.
4. Execute the table creation statements.
5. Execute the INSERT statements.
6. Run the SQL queries from `solution.sql`.
7. Verify the output for each question.

---

## Learning Outcomes

Through this assignment, I gained practical experience with:

* Database design
* Table creation
* Primary and Foreign Keys
* SQL constraints
* Data retrieval
* Filtering records
* Aggregate functions
* Joins
* Transactions
* Query optimization

---

## Author

**Name:** Unnati Agarwal

**Internship:** Celebal Technologies Summer Internship 2026

---

## Acknowledgement

This project was completed as part of the Week 2 SQL Assignment for the Celebal Technologies Summer Internship Program. The implementation follows the database schema and requirements provided in the assignment.
