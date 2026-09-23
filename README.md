# Nike-Sales-Business-Intelligence
Nike Sales Business Intelligence Project

📊 Project Overview

This project presents an End-to-End Business Intelligence solution for analyzing Nike sales performance.

The project transforms raw sales data into meaningful business insights through data cleaning, data transformation, SQL analysis, data warehousing, interactive dashboards, and business recommendations.

The analysis focuses on sales performance across products, customers, regions, categories, and sales channels.

⸻

🎯 Project Objective

The main objective of this project is to analyze Nike’s sales performance and transform raw business data into actionable insights that can support data-driven decision making.

The project follows a complete Business Intelligence workflow:

Raw Business Data → Data Cleaning → Data Transformation → SQL Analysis → Data Warehouse → Data Visualization → Business Insights & Recommendations

⸻

🗂️ Project Workflow

1. Excel – Data Exploration

Excel was used for the initial exploration of the raw sales data.

Key tasks included:

* Understanding the dataset structure
* Identifying missing values
* Detecting duplicate records
* Exploring sales and customer data
* Calculating basic KPIs
* Performing initial data validation

⸻

2. Power Query – Data Cleaning & Transformation

Power Query was used to prepare the dataset for analysis.

Main transformation steps included:

* Removing duplicates
* Handling missing values
* Cleaning text fields
* Standardizing data formats
* Transforming columns
* Correcting data types
* Preparing the data for database analysis

⸻

3. SQL – Data Analysis

SQL was used to perform advanced analytical queries and extract business insights.

The analysis included:

* Revenue analysis
* Customer analysis
* Product performance
* Regional performance
* Category analysis
* Ranking products
* Aggregations
* Subqueries
* CTEs
* Window Functions
* LAG()
* Set Operations
* SQL Views

A dedicated SQL View was also created:

vw_Product_Performance

⸻

🏗️ Data Warehouse

A Star Schema was designed to organize the data for analytical reporting.

Fact Table

FactSales

Contains measurable business metrics such as:

* Sales
* Quantity
* Revenue
* Order information

Dimension Tables

DimCustomer
DimProduct
DimRegion
DimDate

The dimensional model allows efficient analytical queries and supports Power BI reporting.

Star Schema

                    DimCustomer
                         |
                         |
DimProduct ---- FactSales ---- DimRegion
                         |
                         |
                      DimDate

⸻

📈 Key KPIs

The dashboard focuses on several important business metrics:

* Total Revenue
* Total Quantity
* Average Order Value
* Total Order Value
* Revenue Trend
* Revenue by Category
* Revenue by Region
* Top Performing Products

⸻

📊 Power BI Dashboard

Power BI was used to build an interactive dashboard for exploring Nike’s sales performance.

Dashboard Features

* KPI Cards
* Revenue Trend Analysis
* Revenue by Category
* Revenue by Region
* Top 5 Products
* Product Type Filters
* Gender / Audience Filters
* Interactive Data Exploration

Product Categories

The analysis includes categories such as:

* Apparel
* Converse
* Equipment
* Footwear
* Jordan

Audience Segments

* Kids
* Men
* Unisex
* Women

Regions

* Latin America
* APLA
* EMEA
* Greater China

⸻

📊 Tableau

Tableau was also used for advanced visualization and geographic analysis.

The Tableau analysis provides an additional perspective on:

* Regional sales performance
* Geographic distribution
* Product performance
* Sales trends
* Business patterns

⸻

💡 Business Insights

The analysis aims to identify important business patterns such as:

* High-performing products and categories
* Revenue distribution across regions
* Customer purchasing behavior
* Sales trends over time
* Regional opportunities
* Product performance differences

These insights can support strategic decisions related to products, customers, regions, and sales performance.

⸻

🛠️ Tools & Technologies

Tool	Purpose
Excel	Data exploration & initial analysis
Power Query	Data cleaning & transformation
SQL Server	Data analysis & querying
SQL	Advanced analytical queries
Data Warehouse	Dimensional modeling
Power BI	Interactive dashboard
Tableau	Advanced visualization & geographic analysis

⸻

📁 Project Structure

nike-sales-business-intelligence/
│
├── README.md
│
├── Data/
│   ├── Raw_Data/
│   └── Cleaned_Data/
│
├── Excel/
│   └── Nike_Sales_Analysis.xlsx
│
├── SQL/
│   ├── Data_Cleaning.sql
│   ├── Analysis_Queries.sql
│   └── Views.sql
│
├── Data_Warehouse/
│   └── Star_Schema.sql
│
├── Power_BI/
│   └── Nike_Sales_Dashboard.pbix
│
├── Tableau/
│   └── Nike_Sales_Dashboard.twbx
│
├── Dashboard/
│   └── Screenshots/
│
└── Documentation/
    └── Project_Report.pdf

⸻

🚀 End-to-End Architecture

Raw Sales Data
      ↓
Excel
      ↓
Power Query
      ↓
Cleaned Data
      ↓
SQL Server
      ↓
Data Analysis
      ↓
Star Schema
      ↓
Power BI + Tableau
      ↓
Business Insights
      ↓
Recommendations

⸻

🎓 Project Type

Academic / Capstone Project

This project demonstrates practical skills in:

* Data Analytics
* Business Intelligence
* Data Cleaning
* SQL
* Data Warehousing
* Data Visualization
* Dashboard Development
* Business Analysis

⸻

👨‍💻 Skills Demonstrated

* Excel
* Power Query
* SQL
* Data Warehousing
* Star Schema
* Power BI
* Tableau
* Data Visualization
* Business Intelligence
* Data Analysis
* Business Insights

⸻

📌 Disclaimer

The dataset and analysis are used to demonstrate a complete Business Intelligence workflow and should not be interpreted as official Nike financial reporting.

⸻

⭐ Project Summary

This project demonstrates how raw sales data can be transformed into a complete Business Intelligence solution through:

Data Cleaning → SQL Analysis → Data Warehousing → Visualization → Business Insights

The final outcome is an interactive analytical solution designed to support better understanding of Nike sales performance.
