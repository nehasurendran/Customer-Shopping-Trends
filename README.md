# Customer-Shopping-Trends
A data analysis project that shows customer behavior analysis on shopping and arrive at business recommendations.
Overview
This project analyzes customer shopping behavior to uncover purchasing patterns, revenue drivers, and discount usage trends. The analysis transforms raw transactional data into actionable insights, helping businesses understand customer demographics, product performance, and the impact of discounts on sales.

Dataset
Source: Shopping trends dataset (CSV file)
Size: 3,900 rows, 18 columns
Key Columns:
Customer ID, Age, Age Group, Gender
Category, Item Purchased, Purchase Amount
Discount Applied, Season, Review Rating
Subscription Status, Payment Method

Tools & Technologies
Python (Pandas, SQLAlchemy) – Data cleaning, feature engineering, and EDA
PostgreSQL – Data storage and SQL analysis
Power BI Desktop – Interactive dashboard creation
Jupyter Notebook – IDE for Python analysis

Project Steps

Data Loading & Exploration (Python)
Imported dataset using Pandas
Initial inspection with .head() and .info()
Checked for missing values and data types
Standardized column names to snake_case
Feature Engineering (Python)
Created age_group column for segmentation
Added purchase_frequency_days for behavioral analysis

Data Cleaning & Preparation
Ensured correct data types for numerical/categorical fields
Verified consistency in categorical values (e.g., Yes/No for discounts)
Loaded cleaned data into PostgreSQL using SQLAlchemy

SQL Analysis (PostgreSQL)
Total revenue by age group
Discount application rate by item
Top 3 items purchased within each category
Revenue contribution by product category
Power BI Dashboard Development
Connected Power BI to PostgreSQL database
Built interactive Customer Behavior Dashboard with:
KPIs: Customer count, average purchase amount, review rating
Slicers: Subscription status, gender, product category
Visuals: Revenue by category, sales volume, subscription distribution

Dashboard Features
KPIs Displayed:
Total Customers: ~3.9K
Average Purchase Amount: $59.76
Average Review Rating: 3.75

Interactive Filters:
Subscription Status (Yes/No)
Gender (Male/Female)
Product Category (Clothing, Footwear, Outerwear, Accessories)
Key Visualizations:
Donut chart: Percentage of customers by subscription status
Column chart: Revenue by category
Bar chart: Sales volume by category

Key Insights
Age Group Impact: Certain age groups contribute significantly more to total revenue
Discount Patterns: Discounts are more frequently applied to specific product categories
Product Concentration: A small number of items dominate purchases within each category
Seasonal Influence: Seasonal trends strongly influence customer buying behavior
Category Performance: Clothing generates the highest revenue, followed by Accessories and Footwear

Business Recommendations
Customer Loyalty Programs: Implement structured programs to reward repeat customers and improve retention
Discount Policy Review: Analyze discount effectiveness across categories to optimize profitability
Targeted Marketing: Use segmentation based on age, gender, and behavior for personalized campaigns
Product Positioning: Strategically promote high-performing products in top revenue categories

Subscription Growth: Encourage subscription adoption with exclusive benefits and incentives
