# customer_behavior_analysis

## Project Overview

This project focuses on analyzing customer shopping behavior using transactional retail data containing 3,900 purchase records across multiple product categories. The analysis was performed using Python, PostgreSQL, and Power BI to uncover customer purchasing patterns, product preferences, subscription behavior, and revenue insights that can support strategic business decisions.

## Objectives
Analyze customer purchase behavior and spending trends
Identify high-value customer segments
Discover top-performing products and categories
Evaluate the impact of discounts and subscriptions
Build an interactive Power BI dashboard for business insights
## Dataset Information
Dataset Summary
Rows: 3,900
Columns: 18
Data Includes:
Customer demographics
Product purchase details
Shopping behavior metrics
Subscription information
Review ratings and shipping preferences
Key Features
Age
Gender
Location
Subscription Status
Item Purchased
Category
Purchase Amount
Discount Applied
Shipping Type
Review Rating
Purchase Frequency
Data Quality
Missing values found in the Review Rating column
Missing values handled using median imputation by category
## Tech Stack
Tool	Purpose
Python	Data Cleaning & Exploratory Data Analysis
Pandas & NumPy	Data Manipulation
MySQL	SQL Analysis
Power BI	Data Visualization & Dashboarding
Data Cleaning & Feature Engineering

The following preprocessing steps were performed:

Imported and explored the dataset using Pandas
Handled missing values in review ratings
Renamed columns to snake_case format
Created custom age groups
Engineered purchase frequency features
Removed redundant columns
Loaded cleaned data into PostgreSQL for analysis
## SQL Business Analysis

The project answered several business questions using PostgreSQL queries:

Key Analyses Performed
Revenue comparison by gender
High-spending customers using discounts
Top-rated products
Shipping type comparison
Subscriber vs non-subscriber spending
Discount-dependent products
Customer segmentation
Top products by category
Repeat buyers and subscriptions
Revenue contribution by age groups
## Key Insights
Revenue by Gender
Male customers generated significantly higher revenue compared to female customers.
Top Rated Products

Top-performing products based on average ratings:

Gloves
Sandals
Boots
Hat
Skirt
Customer Segmentation

Customers were grouped into:

Loyal Customers
Returning Customers
New Customers

The majority belonged to the loyal customer segment.

Subscription Insights

Non-subscribers contributed higher overall revenue due to larger customer volume, while subscribers showed consistent average spending.

Age Group Revenue

Young adults contributed the highest revenue among all age groups.

## Power BI Dashboard

An interactive Power BI dashboard was created to visualize:

Customer distribution
Average purchase amount
Revenue by category
Sales trends by age group
Subscription insights
Product category performance
## Business Recommendations

Based on the analysis:

Improve subscription benefits to increase conversions
Introduce customer loyalty programs
Optimize discount strategies
Promote top-rated products
Focus marketing campaigns on high-revenue age groups
## Future Improvements
Add predictive analytics for customer churn
Implement recommendation systems
Perform customer lifetime value analysis
Build automated reporting pipelines
📌## Conclusion

This project demonstrates an end-to-end retail data analysis workflow using Python, SQL, and Power BI. The insights generated can help businesses improve customer retention, optimize marketing strategies, and enhance product positioning through data-driven decision-making.
