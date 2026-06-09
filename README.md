# blinkit-grocery-data-analysis
Blinkit grocery data analysis project using SQL for data cleaning (standardizing fat content), Excel for initial validation, and Power BI for building an interactive dashboard to track total sales, average sales, and outlet performance.

# Blinkit Grocery Data Analysis Project

An end-to-end data analysis project utilizing SQL, Excel, and Power BI to analyze Blinkit's grocery sales data, uncover key performance metrics, and optimize outlet performance.

---

## 📊 Business Overview & Objectives
The goal of this project is to evaluate Blinkit's sales data to identify trends, optimize product categories, and understand how various outlet characteristics (size, location, age) impact overall revenue.

### Key KPIs Tracked:
* **Total Sales:** The overall revenue generated from all outlets.
* **Average Sales:** The mean revenue per transaction.
* **Number of Items:** The total volume of items sold across categories.
* **Average Rating:** Customer satisfaction metrics across different product groups.

---

## 🛠️ Tools & Technologies Used

| Tool | Purpose / Use Case | Key Functions Performed |
| :--- | :--- | :--- |
| **Microsoft SQL Server** | Data Cleaning & Transformation | • Standardized inconsistent data (e.g., mapped "LF"/"low fat" to `Low Fat` and "reg" to `Regular`) <br> • Handled missing values and verified data types |
| **Microsoft Excel** | Data Validation & Sanity Checks | • Used Pivot Tables to double-check aggregated totals  • Performed initial data exploration before dashboard ingestion |
| **Power BI Desktop** | Data Modeling & Visualization | • Engineered custom business metrics using **DAX** formulas  • Built interactive charts, cards, and dynamic filter panes |


---

## 📈 Dashboard Insights & Features
The interactive Power BI dashboard breaks down grocery data into several key analytical views:

* **Outlet Performance Analysis:** Comparing sales performance across different outlet sizes (Small, Medium, High) and location tiers (Tier 1, Tier 2, Tier 3).
* **Product Category Breakdown:** Highlighting top-performing item types (e.g., Fruits, Vegetables, Snack Foods) based on total revenue.
* **Establishment Type Metrics:** Evaluating how the year of establishment and outlet type (Supermarket Type 1/2/3 vs. Grocery Store) impacts modern-day sales.

### Dashboard Preview
![Blinkit Dashboard](./Screenshot%202026-06-08%20211934%20blinkit%20dashboard.png)

---

## 📁 Repository Structure
```text
├── BlinkIT Grocery Data.xlsx                           # Raw & validated Excel dataset
├── Screenshot 2026-06-08 211934 blinkit dashboard.png  # Dashboard preview image
└── README.md                                           # Project documentation
