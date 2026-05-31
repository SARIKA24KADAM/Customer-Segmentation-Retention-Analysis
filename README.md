# Customer Segmentation & Sales Analytics Dashboard

A data science project that analyzes customer behavior, segments users using RFM analysis, and visualizes sales performance using interactive dashboards.

Goal: Turn raw retail data into actionable business insights.

Outcome: Identified high-value customers, churn risks, and revenue trends.

## Project Overview
This project analyzes retail transaction data to understand customer behavior, sales performance, and revenue distribution.
- Using customer purchase history, we performed exploratory data analysis (EDA), RFM-based segmentation, and business intelligence visualization to identify high-value customers, at-risk customers, and sales trends over time.
- The goal is to help businesses make data-driven decisions for marketing, retention, and revenue optimization.

## Business Problem
Retail companies often struggle with:

- Identifying high-value customers
- Understanding customer churn risk
- Tracking revenue trends over time
- Optimizing marketing strategies

This project solves these challenges using data analytics and segmentation techniques.

## Dataset Information

The dataset contains transactional retail data with the following features:

- InvoiceNo: Unique transaction ID
- StockCode: Product identifier
- Description: Product name
- Quantity: Items purchased
- InvoiceDate: Transaction date
- UnitPrice: Price per unit
- CustomerID: Unique customer identifier
- Country: Customer location
- TotalPrice: Total transaction value
- Month: Extracted time feature

## Methodology

1. Data Cleaning & Preprocessing
2. Feature Engineering (RFM Analysis)
3. Customer Segmentation using K-Means
4. Exploratory Data Analysis (EDA)
5. Business Intelligence Visualization
6. Dashboard Creation (Static + Animated)

## Key Visualizations

### Monthly Sales Trend
Shows revenue growth over time and seasonal patterns.

### Top Products Sold
Identifies best-selling products driving revenue.

### Top Countries by Revenue
Highlights geographic sales distribution.

### Revenue Distribution
Shows how order values are spread across transactions.

### Customer Segmentation Dashboard
Groups customers into:
- Champions
- Loyal Customers
- At-Risk Customers
- Ultra High Value Customers

## Dashboard Visuals

### Customer Analytics Dashboard
![Dashboard](final_dashboard.png)

### Monthly Sales Trend
![Sales Trend](images/monthly_sales.png)

### Customer Segments
![Segments](images/segment_distribution.png)

### Revenue by Country
![Countries](images/country_sales.png)

## Business Insights

- A small percentage of customers generate majority of revenue (Pareto principle)
- High-value customers show strong frequency and monetary patterns
- Several high-spending customers are at risk due to inactivity
- Seasonal spikes in sales indicate demand-driven purchasing behavior
- Certain countries contribute disproportionately to total revenue

## Tools & Technologies

- Python 
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Impact

This project demonstrates:
- Real-world data analytics workflow
- Customer segmentation using machine learning
- Business intelligence reporting
- Data storytelling for decision-making
