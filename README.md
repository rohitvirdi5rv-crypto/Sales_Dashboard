
# 📊 Power BI Sales Dashboard Project

## 🚀 Project Overview

This project showcases a **fully interactive Sales Dashboard built using Power BI**, designed to transform raw business data into meaningful insights. The dashboard enables users to explore **sales performance, profitability, and product-level insights** through intuitive and dynamic visualizations.

The solution follows a complete **data analytics pipeline**, including:

- Data Collection
- Data Cleaning & Transformation
- Data Modeling
- DAX Calculations
- Dashboard Design & Visualization

---

## 🎯 Project Objectives

The primary objectives of this project are:

- Analyze **sales trends over time**
- Identify **top and bottom-performing products**
- Evaluate **profitability across different dimensions**
- Compare **Sales, Quantity Sold, and Profit**
- Enable **interactive filtering and drill-down analysis**
- Build **a professional BI dashboard for decision-making**

---

# 🔄 End-to-End Data Analytics Workflow

## 1️. Data Collection
- The dataset was sourced from an Excel file
- Contains key business fields such as:
  * Product Details
  * Sales
  * Quantity Sold
  * Profit
  * Dates / Time fields
---

## 2️. Data Cleaning & Transformation (Power Query Editor)

Data preprocessing was performed using **Power Query Editor** in Power BI:

**🔹Cleaning Steps:**
- Removed **null and duplicate values**
- Standardized column formats (Date, Numeric, Text)
- Renamed columns for better readability
- Handled inconsistent or incorrect data entries

**🔹Transformation Steps:**
- Created new calculated columns
- Changed data types (e.g., text → date, string → number)
- Filtered irrelevant rows
- Structured dataset for analysis
---

## 3️. Data Modeling (Model View)

A **relational data model** was created to connect multiple tables efficiently.

**🔗 Key Features:**
- Defined **relationships (1-to-many / many-to-one)**
- Used **Primary Keys & Foreign Keys**
- Enabled **cross-filtering between visuals**

![Dashboard Screenshot](https://github.com/rohitvirdi5rv-crypto/Sales_Dashboard/blob/93d6f99666494aa8045191b9080e74e3d8281766/Dashboard%20Images/Model%20View.png)

**📌 Benefits:**
- Faster query performance
- Accurate aggregations
- Scalable structure for future data additions
---
## 4️. DAX (Data Analysis Expressions)

DAX was used to create **calculated measures and columns** for advanced analysis.

**🔹Key DAX Measures Created:**
- Total Sales
- Total Profit
- Total Quantity Sold
- Profit Margin
- Time-based calculations

**🔹Example:**

      Total Sales = SUM(Sales[Sales Amount])

      Total Profit = SUM(Sales[Profit])

      Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)

      etc.

**🔹Use of DAX:**
- Aggregations (SUM, COUNT, AVERAGE)
- Conditional calculations
- KPI logic creation
- Time Intelligence
- Supporting dynamic visuals

These measures power all dashboard visuals dynamically.

---

# 📊 Dashboard Pages & Features

## 🔹Page 1: Top/Bottom Products Analysis

* Displays **Top & Bottom Products** based on:

  - Sales
  - Quantity Sold
  - Profit

![Dashboard Screenshot](https://github.com/rohitvirdi5rv-crypto/Sales_Dashboard/blob/93d6f99666494aa8045191b9080e74e3d8281766/Dashboard%20Images/Page%201%20-%20TopBottom%20Products%20by%20SalesQuantitySoldProfit.png)

**📌Insights:**

  - Identify best-selling products
  - Detect underperforming items
  - Support inventory and pricing decisions

---

## 🔹Page 2: Sales Over Time

* Line/area charts showing **sales trends**

* Tracks:
  - Growth patterns
  - Seasonal variations
  - Revenue fluctuations

![Dashboard Screenshot](https://github.com/rohitvirdi5rv-crypto/Sales_Dashboard/blob/93d6f99666494aa8045191b9080e74e3d8281766/Dashboard%20Images/Page%202%20-%20Sales%20Over%20Time.png)

**📌Insights:**

  - Helps in forecasting and planning
  - Identifies peak sales periods

---

## 🔹Page 3: Comparative Analysis

* Compares:
  - Sales vs Profit vs Quantity Sold

![Dashboard Screenshot](https://github.com/rohitvirdi5rv-crypto/Sales_Dashboard/blob/93d6f99666494aa8045191b9080e74e3d8281766/Dashboard%20Images/Page%203%20-%20Comparing%20ProfitSalesQuantitySold.png)

**📌Insights:**

  - High sales ≠ high profit
  - Helps identify cost inefficiencies

---

## 🔹Page 4: Dynamic Filtering
* Includes **interactive slicers and filters**
* Users can filter by:
  - Product
  - Category
  - Time period

![Dashboard Screenshot](https://github.com/rohitvirdi5rv-crypto/Sales_Dashboard/blob/93d6f99666494aa8045191b9080e74e3d8281766/Dashboard%20Images/Page%204%20-%20Dynamic%20Filter.png)

**📌Insights:**
* Enables custom analysis for different scenarios
* Enhances user experience
---

# ⚙️ Dashboard Features
## ✅ Interactive Visuals
* Fully responsive charts and graphs
* Cross-filtering enabled across all visuals
## ✅ KPI Indicators
* Key business metrics displayed clearly
## ✅ Drill-Down Capability
* Users can explore data at deeper levels
## ✅ Clean UI/UX Design
* Structured layout for easy navigation
---

## 📈 Business Impact

This dashboard helps businesses to:

- Monitor performance in real-time
- Identify losses and inefficiencies
- Optimize product strategy
- Make data-driven decisions
---

## 🧠 Key Learnings
* Hands-on experience with **Power BI end-to-end workflow**
* Strong understanding of:
  - Data Cleaning
  - Data Modeling
  - DAX Calculations
* Improved skills in:
  - Data Visualization
  - Business Analytics
  - Dashboard Design

---
## 👨‍💻 Author

**Rohit Virdi**  
🎓 BCA + MCA  
💼 Aspiring Data Analyst / Data Scientist  
📊 Passionate about Data Analytics & Visualization

---
## ⭐ Support

If you found this helpful:

* ⭐ Star the repo
* 🍴 Fork it
* 📢 Share it
---
## 📬 Contact

Open to opportunities in:

* Data Analytics
* Data Science
* Business Intelligence

---

✨ This project demonstrates how raw data is transformed into actionable insights using Power BI, combining data analytics, and visualization into one complete solution.

---