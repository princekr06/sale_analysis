# Retail Sales Analysis SQL Project

## Project Overview
**Database:** `sql_project_p2`  
This project demonstrates foundational to intermediate SQL skills used by data analysts to explore, clean, and extract business insights from transactional retail sales data. It walks through setting up the database, handling missing values, exploratory data analysis (EDA), and solving specific business problems using advanced SQL techniques.

---

## Database & Table Schema

```sql
CREATE DATABASE sql_project_p2;

DROP TABLE IF EXISTS retail_sales;
CREATE TABLE retail_sales (
    transaction_id INT PRIMARY KEY,    
    sale_date DATE,     
    sale_time TIME,    
    customer_id INT,
    gender VARCHAR(15),
    age INT,
    category VARCHAR(15),    
    quantity INT,
    price_per_unit FLOAT,    
    cogs FLOAT,
    total_sale FLOAT
);
