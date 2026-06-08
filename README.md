# blinkit-grocery-data-analysis
Blinkit grocery data analysis project using SQL for data cleaning (standardizing fat content), Excel for initial validation, and Power BI for building an interactive dashboard to track total sales, average sales, and outlet performance.
# 🛒 Blinkit Grocery Data Analysis Project

An end-to-end data analysis project focused on evaluating **Blinkit's** sales performance, customer satisfaction, and inventory distribution. This project combines the power of **SQL**, **Excel**, and **Power BI** to transform raw grocery transactional data into actionable business insights.

---

## 📊 Dashboard Preview
![Blinkit Power BI Dashboard](Screenshot%202026-06-08%20211934%20blinkit%20dashboard.png)

---

## 🎯 Project Objective
The goal of this project is to conduct a comprehensive analysis of Blinkit's sales delivery data to uncover hidden trends, optimize product placement, and identify key performance drivers using a multi-tool data pipeline.

---

## 🛠️ Tech Stack & Tool Breakdown

### 1. 🗄️ SQL (Data Extraction & Cleaning)
* **Data Inspection:** Analyzed the initial dataset structure using baseline queries to understand rows and features.
  ```sql
  SELECT * FROM blinkit_data;UPDATE blinkit_data
  
UPDATE blinkit_data
SET Item_Fat_Content = 
    CASE 
        WHEN Item_Fat_Content IN ('LF', 'low fat') THEN 'Low Fat'
        WHEN Item_Fat_Content = 'reg' THEN 'Regular'
        ELSE Item_Fat_Content
    END;
   2. 📊 Microsoft Excel (Exploratory Data Analysis)
Handled missing values, removed duplicates, and cross-checked key data metrics.

Used formulas for initial data verification and quick summary statistics.

3. 📉 Power BI (Data Modeling & Visualization)
Built a dynamic, interactive dashboard to visualize Key Performance Indicators (KPIs).

Implemented advanced DAX measures for complex calculations and dynamic reporting.

Integrated slicers for real-time filtering by outlet location, size, and item type.

📊 Key Metrics Tracked
Total Sales: Overall revenue generated across different outlets.

Average Sales: The average value per transaction.

Number of Items: Total volume of grocery products sold.

Average Rating: Customer satisfaction scores broken down by product categories.

💡 Key Insights Discovered
Product Performance: Identified which grocery categories (e.g., Snacks, Dairy, Fruits & Vegetables) drive the maximum revenue.

Outlet Analysis: Compared sales performance across Tier 1, Tier 2, and Tier 3 cities, revealing that outlet size significantly impacts order volume.
