Title: Reliance Smart & Co Sales and Profitability Dashboard

Overview:
This Power BI dashboard provides comprehensive insights into the sales and profitability performance of Reliance & Co. It leverages interactive visualizations to analyze revenue trends, regional performance, customer segmentation, and product-level profitability. Designed for business stakeholders, the dashboard empowers data-driven decisions through dynamic filters, KPI tracking, and year-over-year comparisons.

Key Features:

Dynamic KPI cards for Sales, Profit, and Margin

Regional and Segment-wise Performance Analysis

Monthly Sales Trend Visualization

Top/Bottom Performing Products and Customers

Interactive Filters for Country, Customer Segment, and Date

Tools Used:

Power BI Desktop

DAX (Data Analysis Expressions)

Power Query (ETL transformations)

Excel (Data source)

Skills Demonstrated:

Data modeling and relationship building

DAX measures and calculated columns

Data cleaning and transformation in Power Query

Business-oriented dashboard design

📄 Detailed Project Report
1. Project Objective
To build a visually compelling and interactive Power BI dashboard that allows Reliance & Co’s management to monitor key sales metrics and profitability insights across different geographies, customer segments, and time periods.

2. Data Sources
Primary data imported from Excel files containing:

Sales Transactions

Customer Information

Product Details

Date Table (used for time intelligence)

3. Data Preparation
Power Query was used for:

Cleaning column names and standardizing formats

Merging related tables (e.g., Sales with Customers and Products)

Removing duplicates and handling null values

Creating a date dimension for time-based calculations

4. Data Model Design
Star schema with:

Fact Table: Sales

Dimension Tables: Customers, Products, Date, Region

Relationships established using primary/foreign keys

Ensured referential integrity for correct aggregations

5. DAX Measures Created
Total Sales = SUM(Sales[Revenue])

Total Profit = SUM(Sales[Profit])

Profit Margin = DIVIDE([Total Profit], [Total Sales])

YoY Growth = CALCULATE([Total Sales], SAMEPERIODLASTYEAR(Date[Date]))

6. Dashboard Design
Top-level KPIs: Total Sales, Profit, Margin

Charts and Visuals:

Line Chart for Monthly Sales Trend

Bar Charts for Top Customers and Products

Map Visual for Regional Sales Distribution

Matrix table for detailed breakdown by Segment and Product Category

Slicers for Interactivity: Country, Segment, Date Range

7. Business Impact
The dashboard allows stakeholders to:

Identify declining or growing regions

Monitor customer segments with high profitability

Detect seasonal trends and peak periods

Track performance of key products and take timely action

