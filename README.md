# Retail Sales Analysis Using SQL

## Project Overview

**Project Title:** Retail Sales Analysis  
**Database:** p1_retail_db  
**Database Management System:** PostgreSQL  
**Project Level:** Beginner

This project focuses on analyzing retail sales data using SQL and PostgreSQL. The main objective is to explore sales transactions, clean the data, and answer business questions to generate meaningful insights.

## Objectives

- Create a retail sales database using PostgreSQL.
- Explore and understand the dataset.
- Identify and handle missing or NULL values.
- Perform data analysis using SQL queries.
- Analyze customer behavior and product categories.
- Identify sales trends and top customers.
- Generate useful business insights.

## Tools & Technologies

- PostgreSQL
- SQL
- pgAdmin 4
- GitHub
- CSV Dataset

## Dataset Information

The dataset contains retail sales transaction records with the following columns:

| Column | Description |
|---|---|
| transactions_id | Unique transaction ID |
| sale_date | Date of sale |
| sale_time | Time of sale |
| customer_id | Customer ID |
| gender | Customer gender |
| age | Customer age |
| category | Product category |
| quantity | Quantity sold |
| price_per_unit | Price per unit |
| cogs | Cost of goods sold |
| total_sale | Total sales amount |

## Project Workflow

### 1. Database Setup
- Create database: `p1_retail_db`
- Create table: `retail_sales`
- Define appropriate data types and constraints.

### 2. Data Exploration
- Count total records.
- Identify unique customers.
- Find distinct product categories.
- Understand the dataset.

### 3. Data Cleaning
- Identify missing and NULL values.
- Remove records with missing data where appropriate.
- Prepare clean data for analysis.

### 4. Data Analysis
Use SQL queries to answer business questions such as:

- Find sales made on a particular date.
- Analyze Clothing category sales.
- Calculate total sales by category.
- Find the average age of Beauty category customers.
- Identify high-value transactions.
- Analyze transactions by gender and category.
- Find the best-selling month in each year.
- Identify the top 5 customers by sales.
- Calculate unique customers in each category.
- Analyze sales across Morning, Afternoon and Evening shifts.

## Key SQL Concepts Used

- CREATE DATABASE
- CREATE TABLE
- SELECT
- WHERE
- DISTINCT
- COUNT()
- SUM()
- AVG()
- GROUP BY
- ORDER BY
- HAVING
- CASE WHEN
- Common Table Expressions (CTEs)
- Window Functions
- RANK()
- EXTRACT()

## Repository Structure

- SQL file – Database setup and analysis queries.
- CSV file – Retail sales dataset.
- README.md – Project documentation.

## Learning Outcomes

Through this project, I practiced:

- Working with relational databases.
- Writing SQL queries.
- Data exploration and cleaning.
- Aggregating and analyzing sales data.
- Solving business problems using SQL.
- Generating insights from retail sales data.

## Conclusion

This project helped me strengthen my SQL fundamentals and understand how data analysts use SQL to explore datasets, analyze customer behavior, and solve real-world business problems.

**Author:** Pranali Lande

**Role:** Aspiring Data Analyst
