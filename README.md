# 📊 Sales Analysis Report

## 📌 Overview
This project analyzes sales data using **Tableau** for visualization and **SQL** for in-depth data exploration. The goal is to derive meaningful insights on revenue trends, customer behavior, and product performance.

---
## 📊 Tableau Insights
The Tableau workbook consists of **11 worksheets** analyzing different aspects of sales performance.

### **📊 Interactive Dashboards**
- **[Dashboard 1](https://public.tableau.com/app/profile/ravi.visvesh.s/viz/sales_analysis_17432478550170/Dashboard1)**
- **[Dashboard 2](https://public.tableau.com/app/profile/ravi.visvesh.s/viz/sales_analysis_2_17432480563910/Dashboard2)**
- **[Dashboard 3](https://public.tableau.com/app/profile/ravi.visvesh.s/viz/sales_analysis_3/Dashboard3)**

### **1️⃣ Sales Distribution & Performance**
- **Dealsize Distribution** 📏 - Shows revenue contribution based on deal size.
- **Price Distribution** 💰 - Analyzes the pricing spread across products.
- **Quantity Distribution** 📦 - Examines the number of units sold across various products.
- **Sale Distribution** 🏷️ - Visualizes overall sales patterns.

### **2️⃣ Regional & Customer Analysis**
- **Sales Per Country** 🌍 - Compares sales revenue across different countries.
- **Sales Per Customer** 👥 - Tracks customer purchases and spending patterns.

### **3️⃣ Time-Based Trends**
- **Sales Per Month and Year** 📆 - Identifies seasonal and yearly trends in sales.
- **Sales Per Year** 📅 - Analyzes total revenue growth over time.

### **4️⃣ Product Performance**
- **Sales Per Product** 📊 - Highlights best-selling products.
- **Sales by Product Line and Year** 🏷️ - Tracks product category performance over multiple years.
- **Sales Per Status** ✅ - Breaks down sales by order status (shipped, pending, etc.).

---
## 🔍 SQL-Based Insights
The SQL queries provide a deeper analysis of the dataset, supporting the Tableau visualizations.

### **1️⃣ Sales Breakdown**
- **Sales Per Product Line** 🛍️ - Identifies top revenue-generating product lines.
- **Sales Per Year** 📅 - Evaluates overall revenue trends.
- **Sales by Deal Size** 📏 - Determines the most profitable deal sizes.

### **2️⃣ Peak Sales Periods**
- **Best Month for Sales Per Year** 🏆 - Finds the highest revenue-generating month.
- **Top Selling Products in Peak Months** 🛒 - Identifies best-selling products during peak periods.

### **3️⃣ Customer Segmentation (RFM Analysis)**
- **Best Customers Analysis** 👑 - Uses Recency, Frequency, and Monetary (RFM) analysis to classify customers:
  - **💀 Lost Customers** - Previously active but now inactive.
  - **🚨 Slipping Away** - At risk of churning.
  - **✨ New Customers** - First-time buyers.
  - **⚠️ Potential Churners** - Showing declining purchase trends.
  - **✅ Active Customers** - Regular buyers.
  - **🏆 Loyal Customers** - High-value, repeat customers.

### **4️⃣ Product Sales Patterns**
- **Orders with Exactly 3 Items Shipped** 📜 - Identifies product bundling patterns using `STRING_AGG`.
