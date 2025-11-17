# Customer Shopping Behavior Analysis – Python | MySQL | Power BI

This project analyzes customer shopping patterns using a full data workflow:
Python → MySQL → SQL Queries → Power BI Dashboard.
The goal is simple: extract meaningful insights about customer spending, product performance, and behavior across demographics and categories.
---
# 📌 Overview

Most dashboards online are just visuals with no real data pipeline behind them.
--This project actually goes end-to-end: 
--Load and clean data in Python
--Store the processed dataset in MySQL
--Run analytical SQL queries
--Build an interactive Power BI dashboard
--Generate insights backed by actual numbers
--If someone wants proof you understand analytics, this repo does it.

---

# 📂 Dataset

Contains customer purchase records

Fields include:

customer_id, gender, age_group, subscription_status

category, purchase_amount, review_rating

shipping_type, order_id, etc.

You can replace with your actual dataset or anonymized sample.

🛠 Tools & Technologies
Step	Tools Used
Data Loading & Cleaning	Python (pandas, numpy)
Database Storage	MySQL
Querying	SQL (MySQL Workbench / Command Line)
Data Visualization	Power BI
Reporting	Power BI + Markdown README
🚀 Project Steps (End-to-End Workflow)
1️⃣ Load Dataset in Python

Import CSV

Handle missing values

Format datatypes

Feature creation (age groups, revenue metrics, etc.)

2️⃣ Insert Cleaned Data into MySQL

Create MySQL schema and table

Connect using sqlalchemy or mysql.connector

Insert cleaned records into the database

3️⃣ Run Analytical SQL Queries

Examples included:

Revenue by category

Customer behavior by age group

Avg purchase amount

Subscription vs non-subscriber comparison

Null value checks and data audits

4️⃣ Connect MySQL to Power BI

Use the MySQL connector

Load processed tables

Build relationships

Create measures using DAX

5️⃣ Build Power BI Dashboard

Key visuals include:

Total Customers

Average Purchase Amount

Average Review Rating

Revenue by Category

Sales by Category

Customer Subscription Breakdown

Revenue & Sales by Age Group

Filters: Gender, Category, Shipping Type, Subscription Status

Screenshot of dashboard:
[/Snapshots/Dashboard.png](https://github.com/YadhunandanC/Customer_Shopping_Behaviour_Dashboard/blob/main/Snapshot%20of%20Dashboard.png)

📊 Dashboard Highlights

Clothing dominates revenue and sales

Only 27% customers are subscribed — huge opportunity

Young Adults and Adults generate the highest revenue

Footwear and Outerwear underperform (needs marketing or bundling)

Average purchase value: $59.76

Average rating: 3.75

This isn't just a pretty dashboard — every insight is backed by queries.

📈 Results & Insights

Subscription Status Matters
Subscribers spend more and purchase more frequently.

Category Performance
Clothing drives majority of the revenue.
Outerwear is the worst performer.

Age Group Trends
Young Adults have the largest order count.
Seniors give fewer transactions but higher average order value.

Shipping Preference
Cost-free delivery options significantly increase sales.
