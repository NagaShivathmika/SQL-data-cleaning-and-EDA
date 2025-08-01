# SQL-Data-Cleaning-and-EDA

SQL Data Cleaning & EDA Project – Layoffs Dataset
Completed as part of Alex The Analyst’s SQL Portfolio Project Series

Overview
This project focuses on cleaning, transforming, and analyzing a real-world layoffs dataset using SQL (MySQL). It was built as part of the Alex The Analyst SQL course, designed to simulate the daily responsibilities of a data analyst working with raw business data.

🧹 Data Cleaning Tasks:

Removed duplicates using ROW_NUMBER() and CTEs.
Standardized values in columns such as company, industry, and country.
Converted inconsistent date formats to a proper DATE column using STR_TO_DATE().
Handled NULL and blank fields using JOIN, conditional logic, and updates.
Removed irrelevant rows (with no layoffs) and unnecessary columns.

📊 Exploratory Data Analysis (EDA):

Total layoffs by company, industry, country, and funding stage.
Identified companies with 100% workforce layoffs.
Aggregated monthly layoff trends.
Computed rolling totals using SUM() OVER.
Ranked top companies by layoffs per year using DENSE_RANK().

🛠 Tools & Concepts Used: 

MySQL
SQL Workbench
Common Table Expressions (CTEs)
Window Functions (ROW_NUMBER(), DENSE_RANK(), SUM() OVER)
Date conversions (STR_TO_DATE())
String & Null handling

📁 Dataset
Original dataset: layoffs.csv (https://www.kaggle.com/datasets/swaptr/layoffs-2022)
Cleaned and transformed in layoffs_staging2 table
Derived insights via SQL queries for final analysis

📈 Key Learnings
Real-world data is messy and inconsistent — and SQL is a powerful tool to clean it
Understanding the business context is critical when analyzing trends
Window functions are essential for advanced analytics like ranking and running totals
