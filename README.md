# Order_Sales-Analysis
End to End Data Analytics Project (Python + SQL)

Project Objective
The primary objective of this project is to analyze retail order data to derive actionable insights. The project includes tasks such as setting up the database, data extraction, transformation, loading, and performing various SQL queries to generate reports on sales performance, product performance, and growth analysis.

Steps Performed
1. Data Acquisition
Data Source: The dataset was sourced from Kaggle (https://www.kaggle.com/datasets/ankitbansal06/retail-orders).
Data File: The dataset file is orders.csv.
2. Environment Setup
Python Libraries: Utilized libraries such as pandas for data manipulation, sqlalchemy for database connection, and kaggle for dataset download.
Database: SQL Server (local instance).
Configuration: Ensured kaggle.json is correctly placed for authentication.
3. Data Preparation
Initial Load: Loaded the dataset into a Pandas DataFrame.
Column Renaming: Renamed columns to have consistent and SQL-compliant names.
Data Cleaning: Handled missing values by replacing 'Not Available' and 'unknown' with NaN.
Data Transformation: Created additional columns for discount, sales_price, and profit based on existing data.
4. Database Operations
Table Creation: Created the df_orders table in SQL Server with the appropriate schema.
Data Insertion: Loaded the cleaned and transformed data from the Pandas DataFrame into the SQL Server table.
5. SQL Queries and Analysis
