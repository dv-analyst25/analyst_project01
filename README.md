#  Sales Data Analysis using Python and SQL

## Overview
This project focuses on analyzing and improving sales performance using **Python (Pandas)** and **SQL**.  
The goal is to clean raw order data, calculate key metrics like profit, revenue, and delivery time, and find insights for better decision-making.

---

## Step 1: Data Cleaning and Preparation (Python)

### Tools Used
- Python  
- Pandas, SQLAlchemy  
- Kaggle API for dataset download  

### Steps Performed
1. Downloaded dataset from Kaggle 
2. Extracted and loaded the data into a Pandas DataFrame  
3. Handled missing values  
4. Converted order and delivery dates into proper datetime format  
5. Calculated new columns:
   - `profit = sale_price - cost_price`
   - `delivery_days = delivery_date - order_date`
6. Dropped unnecessary columns (`list_price`, `cost_price`, `discount_percent`)
7. Loaded the cleaned data into SQL database (`df_orders` table)

**File:** `order data analysis.py`

---

## Step 2: Data Analysis (SQL)

### Database Used
MySQL Workbench (you can also use SQL Server)

### Queries Performed
1. **Top 10 highest revenue-generating products**  
2. **Top 5 highest-selling products in each region**  
3. **Month-over-month sales growth comparison (2022 vs 2023)**  
4. **For each category, find the month with the highest sales**  
5. **Sub-category with highest profit growth (2023 vs 2022)**  

**File:** `sqlCode.sql`

---

## Tools and Technologies
- Python (Pandas, SQLAlchemy)
- MySQL / SQL Server
- Kaggle Dataset
- Jupyter Notebook or VS Code

---

## Files Included
- `order data.py` – Python script for cleaning and loading data  
- `sqlCode.sql` – SQL queries for data analysis  
- `orders.csv` – Raw dataset from Kaggle  
- `README.md` – Project documentation  

---

## How to Run
1. Download dataset using the Kaggle API  
2. Run `data_cleaning.py` to clean and load data into SQL  
3. Open `supply_chain_analysis.sql` in your SQL Workbench and execute the queries  

---

## Author
**Devendra Vishwakarma**  
B.Tech Mechanical Engineering, MANIT Bhopal 
