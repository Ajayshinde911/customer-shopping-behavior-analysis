🛍️ Customer Shopping Behaviour Analysis
One-Line Summary
An end-to-end data analytics project using SQL, Python, and Power BI to uncover consumer purchasing patterns and optimize retail marketing strategies.

Overview
This project analyzes retail customer data to identify high-value segments and shopping trends. It transitions from raw data processing in SQL to exploratory data analysis (EDA) in Python, culminating in an interactive Power BI dashboard for executive-level reporting.

Dataset
Source: final_customer_data.csv.

Content: Contains granular customer information including demographics (age, gender), purchase history, product categories, and spending behavior.

Tools and Technologies
Data Storage & Querying: SQL (PostgreSQL/MySQL) for structured data management.

Data Analysis: Python (Pandas, NumPy) within Jupyter Notebooks for statistical deep-dives.

Data Visualization: Power BI for interactive dashboarding and KPI tracking.

Environment: Jupyter Notebook (.ipynb) for reproducible research.

Methods Used
Database Schema Design: Importing and structuring raw CSV data into relational tables using SQL.

Exploratory Data Analysis (EDA): Using Python to handle missing values, detect outliers, and analyze distributions of customer spend.

RFM Analysis (Recency, Frequency, Monetary): segmenting customers based on their transaction history to identify "Loyal" vs. "At-Risk" groups.

Dashboarding: Creating DAX measures and interactive slicers in Power BI to filter data by region, category, and time.


Key Insights
Demographic Drivers: Identified specific age groups and genders that contribute to the highest share of total revenue.

Category Performance: Discovered which product categories have the highest repeat purchase rate versus one-time buys.

Steps to Run This Project
Database Setup:

Open your SQL editor and run the queries in customer_behaviour.sql to create the table structure and import final_customer_data.csv.

Python Analysis:

Launch the Shopping-behaviour-analysis.ipynb in Jupyter Notebook or Google Colab to view the statistical analysis and data cleaning steps.

Visual Reporting:

Open customer_behaviour.pbix in Power BI Desktop to interact with the visual dashboard (ensure the data source path is updated to your local CSV file).

Seasonal Trends: Analyzed shopping frequency peaks to recommend optimal timing for marketing campaigns.
