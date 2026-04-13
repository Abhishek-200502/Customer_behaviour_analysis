📊 Customer Behavior Analysis & Dashboard
🔹 Overview

This project focuses on analyzing customer behavior using real-world data to extract meaningful insights that can drive business decisions. It demonstrates an end-to-end data analytics workflow, including data cleaning, SQL-based analysis, and interactive dashboard creation.

The project integrates Python, MySQL, and Power BI to transform raw data into actionable insights and visual reports.

🔹 Dataset
The dataset contains customer transaction and behavioral data.
Includes attributes such as:
Customer ID
Purchase history
Product/category details
Transaction date
Revenue and quantity

🔹 Tools & Technologies
Python (Pandas, NumPy) – Data cleaning & preprocessing
MySQL – Data storage, querying, and analysis
Power BI – Dashboard creation & visualization
SQL – Joins, aggregations, filtering, and business queries

🔹 Project Workflow
1️⃣ Data Loading (Python)
Imported raw dataset into Python
Inspected structure, missing values, and data types

2️⃣ Data Cleaning & Preprocessing
Handled missing/null values
Removed duplicates
Standardized formats (dates, categories)
Feature engineering for analysis

3️⃣ Database Integration (MySQL)
Created database and tables
Loaded cleaned data into MySQL
Structured data for efficient querying

4️⃣ SQL Analysis
Customer segmentation
Top customers by revenue
Product/category performance
Purchase frequency analysis
Trend-based queries

5️⃣ Dashboard Creation (Power BI)
Built interactive dashboards
Created KPIs and visual insights
Added filters and slicers for dynamic analysis
🔹 Dashboard Highlights
Open customer_behavior_dashboard.pbix
Create interactive dashboard in Power BI
Identified high-value customers contributing most revenue
Discovered key purchasing patterns and trends
Highlighted top-performing products and categories
Provided actionable insights for improving customer retention and sales
🔹 How to Run the Project
🔸 Step 1: Clone Repository
git clone   https://github.com/Abhishek-200502/Customer_behavior_analysis.git
cd customer-behavior-analysis
🔸 Step 2: Install Dependencies
pip install pandas numpy sqlalchemy mysql-connector-python
🔸 Step 3: Setup Database
Install MySQL
Create database
Update connection string in Python:
create_engine("mysql+mysqlconnector://username:password@localhost:3306/db_name")
🔸 Step 4: Run Python Scripts
Execute data cleaning and loading scripts
🔸 Step 5: Open Power BI Dashboard
Load .pbix file in Power BI Desktop
Connect to database if required

Abhishek Rajput
Aspiring Data Analyst | Python • SQL • Power BI
