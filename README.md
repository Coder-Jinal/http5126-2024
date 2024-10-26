# Database Design and Development
Course Code: HTTP 5126

Academic Year: 2024-2025

This course provides strategies and techniques for designing, creating and interacting with a database. SQL and MySQL languages are the primary focus, with an introduction to NoSQL options.

# links
https://www.geeksforgeeks.org/database-design-ultimate-guide/

# Images
![Workshop Screenshot](Database.png)

> **Notice** : This repository contains essential resources and code examples for database design and development. Familiarity with SQL and MySQL will be beneficial. NoSQL options are briefly introduced to broaden understanding, but the primary focus remains on relational database design.

# SQL:

Some of the SQL commands: 

SELECT * FROM `sales` WHERE item = 1014;

SELECT sales.date, stock_items.item 
FROM sales JOIN stock_items ON sales.item = stock_items.id 
WHERE sales.item = 1014;
 
SELECT * FROM `sales` WHERE employee = 111;

SELECT sales.date, employees.first_name, employees.last_name, sales.item 
FROM sales JOIN employees ON sales.employee = employees.id 
WHERE sales.employee = 111;

