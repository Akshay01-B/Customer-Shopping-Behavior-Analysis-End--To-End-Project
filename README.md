🛍️ Customer Shopping Behavior Analysis
📘 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The goal is to uncover valuable insights into spending patterns, customer segments, product preferences, and subscription behavior to support data-driven business decisions.

📂 Dataset Summary

Total Rows: 3,900

Total Columns: 18

Key Features:

Customer demographics — Age, Gender, Location, Subscription Status

Purchase details — Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping behavior — Discount Applied, Promo Code Used, Frequency, Review Rating, Shipping Type

Missing Data: 37 missing values in the Review Rating column

⚙️ Technologies Used

Python – Data Cleaning, Transformation, and Analysis

PostgreSQL – SQL-based Business Queries and Insights

Power BI – Dashboard Visualization and Reporting

🔍 Exploratory Data Analysis (EDA)

Performed in Python using pandas, numpy, and matplotlib libraries.

Key steps:

Data Loading & Exploration – Checked structure, datatypes, and summary stats.

Data Cleaning – Handled missing values in the Review Rating column using median imputation.

Feature Engineering –

Created age_group from customer age.

Created purchase_frequency_days from purchase history.

Column Standardization – Renamed columns to snake_case.

Database Integration – Loaded cleaned dataset into PostgreSQL for further analysis.

🧮 SQL Analysis

Performed structured queries in PostgreSQL to extract key business insights such as:

Revenue by Gender

High-Spending Discount Users

Top 5 Products by Rating

Shipping Type vs Purchase Amount

Subscribers vs Non-Subscribers

Discount-Dependent Products

Customer Segmentation (New, Returning, Loyal)

Top Products per Category

Repeat Buyers and Subscriptions

Revenue by Age Group

📊 Power BI Dashboard

An interactive dashboard was created in Power BI to visualize:

Revenue by customer demographics

Product performance

Purchase frequency and behavior

Subscription impact on sales

💡 Business Recommendations

Boost Subscriptions: Highlight exclusive subscriber benefits.

Loyalty Programs: Reward repeat customers to increase retention.

Optimize Discounts: Ensure sales boosts don’t reduce margins.

Product Positioning: Promote top-rated and high-selling products.

Targeted Marketing: Focus on high-revenue age groups and express-shipping users.

🧰 Tools & Libraries

Python (Pandas, NumPy, Matplotlib)

PostgreSQL

Power BI

SQLAlchemy
