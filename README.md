# Retail Sales Analytics

Retail Sales Analytics is a SQL practice project built around a retail sales dataset. The repository contains scripts for database setup, table creation, basic queries, joins, subqueries, window functions, stored procedures, and views.

## Project Overview

The goal of this project is to explore retail sales data through progressively more advanced SQL queries. It starts with basic filtering and aggregation, then moves into joins, subqueries, window functions, procedures, and reusable views.

## Repository Structure

```text
Retail-Sales-Analysis/
├── Create_Database.sql
├── Create_Tables.sql
├── Basic_Queries.sql
├── Joins.sql
├── SubQueries_WindowFunctions.sql
├── Procedures.sql
├── Views.sql
├── task.txt
├── Report.MD
├── Dataset/
│   ├── customers.csv
│   ├── orders.csv
│   └── products.csv
└── README.md
```

## Dataset

The project uses three CSV files under the Dataset folder:

- customers.csv: customer details such as CustomerID, CustomerName, Gender, City, and Phone
- products.csv: product details such as ProductID, ProductName, Category, and Price
- orders.csv: order details such as OrderID, CustomerID, ProductID, OrderDate, and Quantity

## Database Schema

The SQL scripts define three core tables:

- Customers
	- CustomerID
	- CustomerName
	- Gender
	- City
	- Phone
- Products
	- ProductID
	- ProductName
	- Category
	- Price
- Orders
	- OrderID
	- CustomerID
	- ProductID
	- OrderDate
	- Quantity

## SQL Coverage

The scripts in this repository cover the following topics:

- Database creation and table setup
- Basic SELECT, WHERE, ORDER BY, DISTINCT, and aggregation queries
- INNER JOIN based sales analysis
- Subqueries for comparisons and rankings
- Window functions such as RANK, DENSE_RANK, and ROW_NUMBER
- Stored procedures for reusable reporting logic
- Views for reusable reporting layers

## File Guide

- Create_Database.sql: creates and selects the RetailSalesDB database
- Create_Tables.sql: creates the Customers, Products, and Orders tables
- Basic_Queries.sql: contains beginner-level retrieval and aggregation queries
- Joins.sql: contains multi-table sales analysis queries
- SubQueries_WindowFunctions.sql: contains subqueries and analytical window-function queries
- Procedures.sql: contains stored procedures for common reporting tasks
- Views.sql: contains reusable reporting views
- task.txt: a task list generated from the SQL queries in the project

## How To Run

1. Run Create_Database.sql to create the database.
2. Run Create_Tables.sql to create the tables.
3. Load the CSV data into the Customers, Products, and Orders tables.
4. Run the remaining SQL files in any order depending on the topic you want to practice.

## Notes

- The repository is designed for SQL learning and practice rather than application development.
- Some advanced reporting queries and views may rely on additional columns or sample data being available in the Orders table, depending on how the dataset is loaded.