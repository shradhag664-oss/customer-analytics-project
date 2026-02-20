# customer-analytics-project

Customer Analytics & Segmentation Dashboard
Project Overview

This project performs end-to-end customer analytics using Python and Power BI to uncover actionable business insights from transactional data.

The objective was to analyze customer purchasing behavior, segment customers using RFM analysis and K-Means clustering, and build an interactive business intelligence dashboard to support strategic decision-making.

 Business Problem

E-commerce businesses must understand:

Who their most valuable customers are

Which customers are at risk of churn

Which product categories drive the highest revenue

How revenue trends change over time

Opportunities to increase Average Order Value (AOV)

This project answers those questions using data-driven analysis.

Key Results
Metric	Value
Total Revenue	₹302.46K
Total Customers	1,454
Average Order Value (AOV)	₹208.02
Customer Segmentation Insights

Using RFM analysis and K-Means clustering, four customer segments were identified:

Segment	Business Interpretation
Champions	High spend, recent buyers, highest revenue contribution
At Risk	Previously active, declining engagement
Active Low Value	Recent buyers but low spending
Lost	Inactive customers with low recent engagement
 Key Insight:

The Champions segment drives the majority of revenue, while the At Risk segment presents an opportunity for retention campaigns.

Methodology
 Data Exploration & Cleaning

Handled missing values

Removed duplicates

Converted date columns

Created Total_Spent feature

Feature Engineering (RFM Model)

Recency → Days since last purchase

Frequency → Number of purchases

Monetary → Total spending per customer

Customer Segmentation

Standardized RFM features

Applied K-Means clustering

Identified 4 customer segments

Business Intelligence Dashboard

Built interactive Power BI dashboard

Created DAX measures

Designed KPI-driven layout

Dashboard Features
KPI Metrics

Total Revenue

Total Customers

Average Order Value
 Revenue by Segment

Visual breakdown of customer segment contribution.
 Revenue by Category

Identifies highest-performing product categories:

Home & Kitchen

Sports

Toys

Clothing

Electronics

Beauty

Books

Monthly Revenue Trend

Shows seasonal revenue patterns and performance trends.
Interactive Filters

Customer Segment

Purchase Date

Payment Method

Tech Stack
Programming & Analysis

Python

Pandas

NumPy

Scikit-learn (K-Means)

Matplotlib

Business Intelligence

Power BI

DAX

Data Modeling

Development Environment

Jupyter Notebook

GitHub
 Project Structure
customer-analytics-project/
│
├── data/
│   ├── raw/
│   └── processed/
│       ├── cleaned_retail.csv
│       └── customer_segments.csv
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   └── 03_customer_segmentation.ipynb
│
├── visualizations/
│   └── dashboard.png
│
├── Customer_Analytics_Dashboard.pbix
└── README.md
Business Recommendations

Launch a VIP loyalty program for Champions to increase retention.

Run targeted discount campaigns for At Risk customers.

Bundle products to increase Average Order Value.

Re-engagement email campaigns for Lost customers.

Optimize marketing investment toward top-performing categories.

Future Enhancements

Customer Lifetime Value (CLV) prediction

Churn prediction model

Cohort analysis

Real-time dashboard integration

Recommendation engine

Author

Shradha Gaikwad
Data Analyst | Business Intelligence | Customer Analytics
