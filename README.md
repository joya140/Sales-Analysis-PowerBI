# Sales-Analysis-PowerBI
Power BI Sales &amp; Budget Analysis Dashboard with Star Schema Data Model, Monthly Budget Comparison, YTD Analysis, Variance Calculation, and KPI Reporting.

 Sales & Budget Performance Analysis Dashboard – Power BI
 Project Overview

This project presents a comprehensive Sales & Budget Analysis solution built using Power BI.
The dashboard analyzes daily sales data (2024–2026) and compares actual sales performance against monthly budget targets.

The objective of this project is to provide actionable business insights through structured data modeling and advanced DAX calculations.

Dataset Information

The project includes:

Fact_Sales Table (Daily Sales Data)

Customer Master Table

Item Master Table

Route Master Table

Budget Table (Monthly Budget Data)

Calendar Table (Date Intelligence)

 Note: The dataset used in this project is sample generated data for demonstration purposes.

 Data Model

A Star Schema data model has been implemented:

Fact_Sales (Fact Table)

Budget_Table (Fact Table)

Customer_Master (Dimension)

Item_Master (Dimension)

Route_Master (Dimension)

Calendar (Dimension)

Relationships are created using primary keys such as:

Item_Code

Route_Code

Route_Customer_ID

Date / YearMonth
