# Task_2_Data_Visualization_and_Storytelling 
Elevate Labs Data Analyst Internship
<br>
Date: June 24, 2025
<br>
Author: Mehvish Idreesi
<br>

## 📝 Objective  
The goal of this task was to create a **Power BI Dashboard** based on a given supermarket sales dataset. The dashboard visualizes total and net revenue, sales distribution across regions, units sold by category, and payment methods, enabling performance insights and executive-level decision making.

---

## 🧹 Data Transformation
Performed in **Power Query Editor**:
- Removed duplicates and error rows to ensure clean data.
- Created calculated columns:
  1. **Total Discount** = Total Revenue - (Total Revenue × (1 - Discount))  
     (Changed data type to *Decimal Number*)
  2. **Net Revenue** = Total Revenue - Total Discount  
     (Changed data type to *Decimal Number*)

---

## 📁 Files in this Repository

| File Name                          | Description                                         |
|-----------------------------------|-----------------------------------------------------|
| `sales_data.csv`                  | Dataset used for building the dashboard             |
| `supermarket_sales_dashboard.pbix`| Power BI file containing the final dashboard        | 
| `dashboard_image.png`             | Image preview of the dashboard                      | 
| `data_transformation_image.png`   | Image preview of the data transformation steps      |
| `README.md`                       | This file – summary of the project                  |

---

## 📊 Dashboard Components

- **Gauge Chart**: Total Revenue vs Target
- **Cards**: 
  - Average Total Revenue  
  - Average Net Revenue  
- **Bar Chart**: Revenue by Region (Total and Net)
- **Line Chart**: Revenue (Total and Net) by Category over time
- **Pie/Donut Charts**:
  - Payment Method Distribution  
  - Units Sold by Category  
- **Column Chart**: Monthly Net Revenue
- **Table**: Summary of Region-wise Sales Metrics

---

## 🔧 Tools Used
- Microsoft Power BI
- Power Query Editor
- DAX Calculated Columns

---

## 📈 Insights Derived
- Central region is the top contributor to overall revenue.
- Cash, Credit Card, and UPI are the most used payment methods.
- Monthly revenue trends indicate March and October as peak months.

---

## ✅ Outcome
- Designed a visually rich, interactive dashboard summarizing key business metrics.
- Practiced data modeling, transformation, and storytelling through visualization.
- Improved familiarity with executive dashboard requirements and KPI tracking.
