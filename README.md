Customer Shopping Behaviour Analysis

A complete end-to-end data analytics project using Python, MySQL (SQL), and Power BI to analyze customer shopping behaviour, identify key trends, and generate actionable business insights.

Project Overview:- 

This project aims to understand how customers interact with products, pricing, discounts, and subscriptions using real transactional data. The analysis identifies important patterns such as customer spending behavior, discount dependency, product performance, subscription value, and demographic trends.

Using Python for data cleaning, SQL for deep analysis, and Power BI for visualization, the project converts raw data into meaningful insights that can support business decisions related to marketing, pricing, product strategy, and customer retention.

Dataset Summary:-

1. Rows: 3,900
2. Columns: 18
3. Type: Customer transactions + demographics + behaviour
4. Contains:
- Age, Gender, Location
- Purchase Amount & Frequency
- Product Categories
- Review Ratings
- Discounts Used
- Subscription Status
- Shipping Type

Missing values in Review Ratings were filled using median imputation, and redundant columns were removed to ensure data quality.

Workflow / Project Pipeline:- 
1️. 
- Data Cleaning & Preparation (Python)
- Loaded dataset using Pandas
- Inspected structure and summary statistics
- Handled missing values using median imputation
- Removed duplicate and redundant fields
- Standardized column names
- Engineered features (Age Groups, Purchase Frequency)
- Uploaded cleaned dataset into PostgreSQL database

2️. SQL-Based Deep Analysis (PostgreSQL)
Key SQL queries performed:

- Revenue by Gender & Age Group
- Top-rated products & most-selling categories
- Discount-dependent items
- Subscriber vs Non-Subscriber Spending
- Customer Segmentation (New, Returning, Loyal)
- Shipping Type comparison
- High-spending discount users
- Top 3 products per category

3️. Dashboard & Visualization (Power BI)
Created an interactive Power BI dashboard including:

- Revenue distribution
- Customer segmentation
- Product performance
- Discount analysis
- Subscription insights
- Shipping behaviour
- Age & gender analytics

Tech Stack:- 

Category	    |   Tools Used
Programming	    |   Python (Pandas, NumPy)
Database	    |   PostgreSQL (pgAdmin4)
Query Language  |   SQL
Visualization	|   Power BI
Environment	    |   Jupyter Notebook
Version Control	|   Git & GitHub

Project Folder Structure:- 

Customer-Shopping-Behaviour-Analysis/
│
├── data/
│   └── raw_dataset.csv
│
├── scripts/
│   ├── data_cleaning.ipynb
│   ├── feature_engineering.ipynb
│   └── sql_queries.sql
│
├── dashboard/
│   └── powerbi_dashboard.pbix
│
├── results/
│   └── final_report.pdf
│
├── README.md
└── requirements.txt

Key Results:- 

-Female customers generated slightly higher revenue depending on the dataset distribution.
-Subscribers spent more and purchased more frequently than non-subscribers.
-Express shipping users formed a premium segment with higher average purchase amounts.
-Several products showed high discount dependency, indicating pricing optimization needs.
-Loyal customers contributed significantly to recurring revenue.
-Top-rated products aligned with best-selling categories, indicating strong product satisfaction.

Business Recommendations:- 

-Promote subscription programs through exclusive benefits.
-Use loyalty points or personalized offers to retain returning customers.
-Limit excessive discounts on products identified as discount-dependent.
-Highlight top-rated items in marketing campaigns.
-Target high-performing age groups and express-shipping users with specialized advertising.
