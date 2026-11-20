# Amazon Sales Analysis Dashboard | Power BI

## 📌 **Project Overview**

This project focuses on analyzing Amazon sales data using Microsoft Power BI. The main objective is to transform raw sales data into meaningful business insights through data cleaning, calculated columns, DAX measures, and interactive dashboards.

The dashboard provides an overview of sales performance, product analysis, regional performance, and customer purchasing patterns.

## 🎯 **Project Objectives**

- Analyze overall sales performance.
- Identify top-performing product categories and products.
- Track monthly sales trends.
- Analyze regional sales performance.
- Understand customer payment preferences.
- Identify key business insights to support decision-making.

## 📂 **Dataset Overview**

- **Dataset Name:** Amazon Sales Dataset
- **Total Records:** 6,000 rows
- **Total Columns:** 10
- **Time Period:** January 2023 – December 2024

### **Dataset Columns**

| Column Name | Description |
|---|---|
| Order_ID | Unique order identifier |
| Order_Date | Date of the order |
| Category | Product category |
| Product_Name | Name of the product |
| Quantity | Number of units purchased |
| Price | Unit price |
| Sales | Total sales amount |
| Region | Sales region |
| Customer_Name | Customer name |
| Payment_Method | Payment method used |

## 🛠️ **Tools & Technologies**

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Visualization
- Data Cleaning & Transformation

## 🧹 **Data Cleaning & Transformation**

The following data cleaning steps were performed using Power Query:

- Promoted the first row as column headers.
- Changed data types appropriately.
- Removed unnecessary spaces from text columns.
- Standardized region names.
- Removed 180 duplicate rows.
- Handled 508 rows containing missing values.
- Filtered invalid quantity values.
- Recalculated the Sales column.
- Loaded the cleaned data into the Power BI data model.

### **Data Cleaning Summary**

| Description | Count |
|---|---:|
| Original Rows | 6,000 |
| Duplicate Rows Removed | 180 |
| Rows with Missing Values | 508 |
| Final Clean Orders | 5,820 |

## 📊 **Calculated Columns**

The following calculated columns were created using DAX:

1. **Order Month** – Extracts the month and year from the order date.
2. **Order Year** – Extracts the year from the order date.
3. **Price Tier** – Categorizes products into Premium, Mid, and Budget segments.
4. **Is Weekend Order** – Identifies whether an order was placed on a weekday or weekend.

## 📐 **DAX Measures**

The following DAX measures were created to calculate important business KPIs:

- Total Sales
- Total Orders
- Units Sold
- Average Order Value (AOV)
- Total Customers
- Sales MoM % Change
- Top Category Sales
- % of Total Sales

## 📈 **Dashboard Pages**

The dashboard consists of **3 interactive pages**.

### 1. Sales Overview

Provides an overall view of sales performance.

**Visualizations:**
- Monthly Sales Trend – Line Chart
- Sales by Payment Method – Donut Chart
- Sales by Region – Bar Chart

### 2. Product Analysis

Focuses on product and category performance.

**Visualizations:**
- Sales by Category – Horizontal Bar Chart
- Top 5 Products by Sales – Column Chart
- Quantity Sold by Category – Clustered Column Chart

### 3. Regional & Customer Analysis

Analyzes regional order performance and customer payment preferences.

**Visualizations:**
- Total Orders by Region – Bar Chart
- Regional Sales Share – Donut Chart
- Orders by Payment Method – Column Chart

## 🔍 **Key Business Insights**

- **Furniture leads in revenue:** Furniture generated ₹2.15 Cr, contributing approximately 34% of total sales, despite having the lowest unit sales among categories.
- **Balanced Regional Performance:** South recorded the highest sales at ₹1.29 Cr, while sales remained relatively evenly distributed across regions.
- **Payment Preferences:** Credit Card and Debit Card contributed the highest sales, while UPI accounted for ₹93.5 L.
- **Data Quality:** Duplicate and incomplete records highlighted the importance of data cleaning before analysis.

## 💡 **Business Recommendations**

- Focus on high-revenue categories such as Furniture and Electronics.
- Investigate the October sales dip to understand possible seasonal trends.
- Encourage digital payment methods such as UPI and Amazon Pay.
- Automate Power Query cleaning steps to maintain data quality during future refreshes.

## 📁 **Project Files**

| File Name | Description |
|---|---|
| amazonsales.pbix | Power BI dashboard file |
| Amazon Sales_Analysis.pptx | Project presentation |
| README.md | Project documentation |
| amazon_sales.csv | Project dataset |
| amazonsales.pdf | Exported pdf from PowerBIdashboard |

## 📷 **Dashboard Preview**

### 1. Sales Overview
![Sales Overview](images/Overview.png)

### 2. Product Analysis
![Product Analysis](images/Overview.png)

### 3. Regional & Customer
![Regional and Customer](images/Overview.png)


## 🚀 **Project Outcome**

This project demonstrates how raw sales data can be transformed into an interactive Power BI dashboard using Power Query, calculated columns, and DAX measures.

It helps identify sales trends, top-performing categories, regional performance, and customer payment preferences, supporting better business decision-making.

## 👩‍💻 Author

[Anjana P C]
**Amazon Sales Analysis – Power BI Project**

