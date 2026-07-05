# Exploratory Data Analysis (EDA) of E_Commerce Sales Data
# Project 1  and 2 Overview 
# This project focuses on performing Exploratory Data Analysis (EDA) on a retail sales dataset containing 1,200 customer transactions. The objective was to explore the data, identify trends and patterns, detect outliers, analyze relationships between variables, and generate business insights to support data-driven decision-making.
# Objectives
1. Perform descriptive statistical analysis.
2. Identify sales trends and purchasing patterns.
3. Detect outliers in numerical variables.
4. Conduct correlation analysis between numerical features.
5. Generate actionable business recommendations.
# Tools Used
* Microsoft Excel
* Python (Pandas, Matplotlib, Seaborn)
* GitHub
# Dataset
The dataset contains 1,200 retail transactions with variables including:
1. Date
2. Product
3. Quantity
4. Unit Price
5. Items in Cart
6. Total Price
7. Payment Method
8. Customer Information
# Data Preparation
* Before analysis, the dataset was cleaned by:
* Removing duplicate records.
* Handling missing values( About 309 missing value in the coupon code column, Hence "NO COUPON" was assigned)
* Correcting data types.
* Checking for data integrity.
* Preparing the dataset for analysis.
* Exploratory Data Analysis
* Descriptive Statistics
# Calculated:
Mean
Median
Count
Minimum
Maximum
Standard Deviation
# Key finding:
* Customers purchased an average of approximately three items per transaction.
* Average transaction value was approximately 1,054.
# Sales Trend Analysis
* Monthly and quarterly sales trends were analyzed using Pivot Tables and charts.
# Key findings:
* 2023 recorded the highest total sales.
* 2025 recorded the lowest sales because only the first half of the year was available.
* January consistently recorded strong sales performance.
* Sales generally performed better during the first quarter.
# Outlier Detection
* Box plots were created for:
Quantity
Unit Price
Total Price
# Findings:
* No outliers were detected for Quantity or Unit Price.
* Eight  high-value outliers were identified in Total Price, representing unusually expensive transactions.
# Correlation Analysis
The following relationships were identified:
Variables
Correlation
* Quantity vs Unit Price = 0.015
* Quantity vs Total Price = 0.62
* Quantity vs Items in Cart = 0.65
* Items in Cart vs Total Price = 0.39
* Unit Price vs Total Price = 0.72
* Unit Price vs Items in Cart = 0.0006
# Key insights:
* Total Price has a strong positive relationship with Quantity and Unit Price.
* Quantity and Unit Price have almost no relationship.
* Product price significantly influences revenue.
* Larger cart sizes only moderately increase total transaction value.
* Online Payment method had the highest count.
* Chair was the overall best selling product across.
# Business Recommendations
* Promote premium products to increase revenue.
* Encourage customers to purchase more items through bundle offers and promotions.
* Run targeted marketing campaigns during lower-performing months.
* Monitor high-value transactions to better understand valuable customer segments.
# Conclusion
* This exploratory data analysis revealed important patterns in customer purchasing behaviour and sales performance. The analysis identified key revenue drivers, seasonal sales trends, significant correlations between variables, and a small number of high-value outlier transactions. These insights can support better business decisions in pricing, marketing, inventory management, and customer engagement.

