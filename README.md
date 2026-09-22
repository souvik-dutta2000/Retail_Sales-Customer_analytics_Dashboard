# Retail_Sales-Customer_analytics_Dashboard

# 📊 Retail Sales & Customer Analytics Dashboard

## 📌 Project Overview

This project analyzes retail sales and customer data to understand **sales performance, profitability, product performance, and customer behavior**.

The project demonstrates an end-to-end data analytics workflow using **Microsoft Excel and Power BI**, starting from data cleaning and preparation through to interactive dashboard development.

### Project Workflow

**Raw Data → Data Cleaning → Excel Analysis → Data Preparation → Power BI Data Modeling → DAX Measures → Interactive Dashboard → Business Insights**

---

## 🎯 Business Objectives

The main objectives of this project are to:

* Analyze overall sales and profit performance
* Identify top-performing products
* Identify high-value customers
* Analyze customer segments
* Understand regional and city-level sales
* Analyze monthly sales trends
* Identify products with high sales but relatively low profit
* Track important business KPIs
* Provide interactive visual analysis through Power BI

---

## 🛠️ Tools & Technologies

* **Microsoft Excel**
* **Power Query**
* **Microsoft Power BI**
* **DAX**
* Data Cleaning
* Data Transformation
* Data Modeling
* Data Visualization
* Business Analytics

---

# 📗 Excel Data Analysis

Excel was used for **data cleaning, transformation, calculations, and exploratory analysis** before building the Power BI dashboard.

### 🔹 Data Cleaning

The following activities were performed:

* Checked and handled missing values
* Standardized data
* Handled missing customer names
* Handled missing city values
* Handled missing discount values
* Created calculated columns
* Validated data consistency

### 🔹 Excel Functions Used

* XLOOKUP
* INDEX-MATCH
* IF
* IFS
* SUMIFS
* COUNTIFS
* TEXT
* DATE
* ROUNDUP

### 🔹 Excel Analysis

Pivot Tables and Pivot Charts were created to analyze:

* Sales performance
* Profit performance
* Product performance
* Customer performance
* Regional performance
* Customer segments

---

# 📊 Power BI Data Preparation & Modeling

The cleaned data was structured into four main tables for Power BI.

### Sales Table

Contains transactional information such as:

* Order ID
* Customer ID
* Product ID
* Quantity
* Discount
* Sales
* Cost
* Profit
* Profit Margin
* Payment Mode
* Shipping Days
* Sales Channel
* Customer Rating
* Discount Percentage

### Customers Table

Contains:

* Customer ID
* Customer Name
* Segment
* City
* State
* Region

### Products Table

Contains:

* Product ID
* Product Name
* Category
* Sub Category
* Unit Price

### Orders Table

Contains:

* Order ID
* Order Date
* Order Month
* Order Status

The tables were connected in Power BI using appropriate keys such as **Customer ID, Product ID, and Order ID**.

---

# 📈 Power BI Dashboard

An interactive Power BI dashboard was created to monitor retail business performance.

## 🔹 Key Performance Indicators (KPIs)

The dashboard includes:

* **Total Sales**
* **Total Profit**
* **Total Orders**
* **Profit Margin**
* **Average Order Value**
* **Total Customers**
* **Total Products**
* **Total Quantity**

---

# 📅 Sales Analysis

The dashboard provides analysis of:

* Monthly Sales Trend
* Sales by Customer Segment
* Sales by Region
* Sales by City
* Overall Sales Performance

---

# 📦 Product Analysis

Product performance was analyzed using:

* Top 10 Products by Sales
* Sales by Category
* Sales by Sub-Category
* Total Quantity
* Sales vs Profit analysis

The Sales vs Profit analysis helps identify products with:

* High Sales + Low Profit
* High Sales + High Profit
* Low Sales + High Profit
* Low Sales + Low Profit

---

# 👥 Customer Analysis

Customer analysis includes:

* Top 10 Customers by Sales
* Sales by Customer Segment
* Customer Value Segmentation
* Sales by City
* Customer Rating Analysis
* Regional Customer Performance

---

# 🧮 Important DAX Measures

### Total Sales

```DAX
Total Sales = SUM(Sales[Sales])
```

### Total Profit

```DAX
Total Profit = SUM(Sales[Profit])
```

### Total Orders

```DAX
Total Orders = DISTINCTCOUNT(Sales[Order ID])
```

### Total Customers

```DAX
Total Customers = DISTINCTCOUNT(Sales[Customer ID])
```

### Total Products

```DAX
Total Products = DISTINCTCOUNT(Sales[Product ID])
```

### Total Quantity

```DAX
Total Quantity = SUM(Sales[Quantity])
```

### Profit Margin

```DAX
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
```

### Average Order Value

```DAX
Average Order Value = DIVIDE([Total Sales], [Total Orders], 0)
```

---

# ❓ Business Questions & KPI Analysis

The dashboard was designed to answer the following business questions.

### Sales Performance

1. What is the total sales revenue?
2. What is the monthly sales trend?
3. Which customer segment generates the highest sales?
4. Which region generates the highest sales?
5. Which cities contribute the most sales?

### Profitability

6. What is the total profit?
7. What is the overall profit margin?
8. Which products generate the highest profit?
9. Which products have high sales but relatively low profit?
10. Which categories contribute the most profit?

### Product Performance

11. What are the Top 10 products by sales?
12. Which product categories perform best?
13. Which products have high quantity but lower revenue?

### Customer Performance

14. Who are the Top 10 customers by sales?
15. Which customer segment generates the most revenue?
16. Which customers belong to High, Medium, and Low Value segments?
17. Which cities have the highest customer sales?
18. How do customer ratings vary across regions and segments?

### Overall Business Performance

19. What is the Average Order Value?
20. How many unique customers and products are there?
21. How does discounting affect sales and profitability?
22. Which areas require further business investigation?

---

# 💡 Key Business Insights

The dashboard can be used to identify:

* Overall sales and profitability performance
* High-performing products
* High-value customers
* Customer segments contributing to revenue
* Regional and city-level sales patterns
* Products requiring profitability investigation
* Monthly sales trends
* Customer behavior patterns

---

# 🖼️ Dashboard Screenshots

## Excel Analysis

Add your Excel analysis screenshot here.

## Power BI Dashboard

Add your Power BI dashboard screenshot here.

## Sales Analysis

Add your Sales Analysis screenshot here.

## Product Analysis

Add your Product Analysis screenshot here.

## Customer Analysis

Add your Customer Analysis screenshot here.

---

# 📁 Project Files

### Excel Analysis

`Retail_Sales_Excel_Analysis.xlsx`

Contains the Excel data cleaning, formulas, calculations, Pivot Tables, and analysis.

### Power BI Data Model

`PowerBI_Data_Model.xlsx`

Contains the structured Sales, Customers, Products, and Orders tables used for Power BI.

### Power BI Report

`Retail_Sales_Customer_Analytics.pbix`

Contains the Power BI data model, DAX measures, visualizations, and interactive dashboard.

---

# 🎓 Skills Demonstrated

* Data Cleaning
* Data Preparation
* Microsoft Excel
* XLOOKUP
* Pivot Tables
* Power Query
* Power BI
* DAX
* Data Modeling
* KPI Development
* Data Visualization
* Sales Analytics
* Customer Analytics
* Product Analytics
* Profitability Analysis
* Business Intelligence
