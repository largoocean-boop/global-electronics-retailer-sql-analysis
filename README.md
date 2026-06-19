# global-electronics-retailer-sql-analysis
SQL-based business intelligence analysis of a global electronics retailer dataset, featuring revenue analysis, customer insights, product performance, store analytics, and geographic sales trends using SQLite.
# Global Electronics Retailer SQL Analysis

## Overview

This project analyzes retail sales data for a global electronics retailer using SQL. The goal of the project is to evaluate revenue performance, product category trends, customer behavior, store performance, and geographic sales patterns using relational data across multiple tables.

The analysis was completed in DB Browser for SQLite and demonstrates SQL joins, aggregations, data cleaning, date handling, revenue calculations, and business intelligence reporting.

## Dataset

The project uses the Global Electronics Retailer dataset, which includes multiple related tables:

- Customers
- Sales
- Products
- Stores
- Exchange Rates

## Business Questions Answered

1. How many products, customers, and stores are in the dataset?
2. What is total revenue?
3. Which product categories generate the most revenue?
4. Which countries generate the most revenue?
5. Who are the top customers by revenue?
6. What are the top products by revenue?
7. How has revenue changed by year?
8. Which countries or channels generate the most revenue per store?
9. Which store locations are the highest performers?

## Key Findings

- Total Revenue: $55.76M
- Total Products: 2,517
- Total Customers: 15,266
- Total Stores: 67
- Computers generated the highest category revenue at $19.3M.
- The United States generated the highest total revenue at $23.76M.
- The Online channel generated $11.4M from a single sales channel.
- Canada had the highest revenue per physical store at $1.20M.
- Revenue peaked in 2019 at $18.26M.
- Top revenue products were concentrated in desktop PCs and large HDTVs.

## Tools Used

- SQL
- DB Browser for SQLite
- CSV Data Import
- Relational Database Analysis
- Business Intelligence Reporting

## SQL Skills Demonstrated

- SELECT statements
- INNER JOINs
- Aggregations with SUM, COUNT, and AVG
- GROUP BY
- ORDER BY
- LIMIT
- Data cleaning using CAST and REPLACE
- Date extraction using SUBSTR
- Revenue calculations
- Multi-table analysis

## Project Files

- `SQL_Queries.sql` - SQL queries used for analysis
- `README.md` - Project documentation
- Dataset files - Customers, Sales, Products, Stores, and Exchange Rates

## Project Goal

To demonstrate the ability to use SQL in a business intelligence context by joining multiple datasets, calculating key performance indicators, identifying revenue trends, and communicating actionable business insights.

