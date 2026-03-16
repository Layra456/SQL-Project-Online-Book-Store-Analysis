📊 Project Overview

This project analyzes an Online Book Store database using SQL.

The goal of this project is to practice and demonstrate core SQL and database analysis skills, including:

Writing complex SQL queries

Working with relational database structures

Analyzing business data

The database simulates a real-world online bookstore system where customers place orders for books.

🗂 Database Schema

This project contains three main tables.

Customers
Column	Description
customer_id	Unique customer ID
name	Customer name
email	Customer email
city	Customer city
Books
Column	Description
book_id	Unique book ID
title	Book title
author	Book author
price	Book price
Orders
Column	Description
order_id	Unique order ID
customer_id	Customer placing the order
book_id	Book being ordered
quantity	Number of books purchased
order_date	Date of order
🔗 Table Relationships
Customers
    │
    │ customer_id
    ▼
Orders
    ▲
    │ book_id
    │
Books

A customer can place multiple orders

A book can appear in multiple orders

The Orders table links Customers and Books

🔍 SQL Concepts Demonstrated

This project uses several important SQL concepts:

INNER JOIN

LEFT JOIN

GROUP BY

ORDER BY

Aggregation Functions

SUM()

COUNT()

AVG()

MAX()

Subqueries

Views

📈 Business Questions Solved

The SQL queries in this project answer the following business questions:

1️⃣ Which customers ordered which books?

2️⃣ How many books did each customer order?

3️⃣ What is the most expensive book?

4️⃣ Which customer ordered the most books?

5️⃣ Which books were never ordered?

6️⃣ How much revenue did each book generate?

7️⃣ Which customers ordered books more expensive than the average book price?

8️⃣ Which book generated the highest revenue?

9️⃣ How many orders came from each city?

🔟 Which customers spent the most money?

⭐ SQL View Created

A view was created to simplify order analysis.

View: Order_Details

This view displays:

Customer Name

Book Title

Quantity

Price

Total Cost

🛠 Tools Used

MySQL

MySQL Workbench

GitHub

🎯 Purpose of the Project

This project was built to:

Practice SQL queries

Understand relational database design

Perform data analysis using SQL

Build a portfolio project for a future Data Analyst career
