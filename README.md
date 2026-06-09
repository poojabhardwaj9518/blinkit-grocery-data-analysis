# blinkit-grocery-data-analysis
Blinkit grocery data analysis project using SQL for data cleaning (standardizing fat content), Excel for initial validation, and Power BI for building an interactive dashboard to track total sales, average sales, and outlet performance.
# Blinkit Grocery Data Analysis Project

An end-to-end data analysis project utilizing **SQL** for data cleaning and standardization, **Excel** for initial data validation, and **Power BI** to build an interactive dashboard tracking key performance indicators (KPIs) and grocery outlet metrics.

---

## 📊 Business Overview & Objectives
The goal of this project is to analyze Blinkit's grocery sales data to uncover insights regarding product performance, outlet characteristics, and customer purchasing patterns. 

### Key KPIs Tracked:
* **Total Sales:** The overall revenue generated from all outlets.
* **Average Sales:** The mean revenue per transaction.
* **Number of Items:** The total volume of items sold across categories.
* **Average Rating:** Customer satisfaction metrics across different product groups.

---

## 🛠️ Tech Stack & Workflow

### 1. Data Cleaning & Transformation (SQL)
* **Fat Content Standardization:** Addressed data entry inconsistencies by standardizing variations like "LF", "low fat" to `Low Fat` and "reg" to `Regular`.
* **Data Quality Checks:** Identified and handled missing values, duplicate entries, and verified data types.

### 2. Initial Validation (Excel)
* Utilized Pivot Tables and basic aggregation formulas to perform quick sanity checks and verify that the dataset matched foundational business rules before dashboard ingestion.

### 3. Interactive Visualization (Power BI)
* Developed a dynamic dashboard to visually represent data and enable granular filtering.
* **DAX Formulas:** Created custom measures to calculate dynamic KPIs, year-over-year trends, and average values.

---

## 📈 Dashboard Insights & Features
The Power BI dashboard breaks down grocery data into several key analytical views:

* **Outlet Performance Analysis:** Comparing sales across different outlet sizes (Small, Medium, High) and location tiers (Tier 1, Tier 2, Tier 3).
* **Product Category Breakdown:** Highlighting top-performing item types (e.g., Fruits, Vegetables, Snack Foods) based on total revenue.
* **Establishment Type Metrics:** Evaluating how the year of establishment and outlet type (Supermarket Type 1/2/3 vs. Grocery Store) impacts modern-day sales.

---

## 📁 Repository Structure

├── BlinkIT Grocery Data.xlsx                  # Raw/Validated Excel dataset
├── Screenshot 2026-06-08 211934 dashboard.png # Visual preview of the Power BI dashboard
└── README.md                                  # Project documentation
