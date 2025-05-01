
# 🚗 Car Sales Analysis Dashboard – Power BI Project

This project presents a professional, interactive dashboard built in Power BI to analyze and monitor car sales performance across various brands, regions, body styles, and Colour. The goal was to extract actionable insights to support sales strategies, inventory planning, and customer behavior analysis.

---

## 📌 Project Objective

To analyze historical and current car sales data using Power BI and DAX, uncover performance trends across brands and regions, and deliver meaningful, quantifiable insights that assist stakeholders in making data-driven decisions to increase sales, identify opportunities, and optimize dealership strategies.

---

## 🛠️ Tools Used

- **Power BI** – Data visualization & dashboard creation  
- **Power Query** – Data cleaning & transformation  
- **DAX (Data Analysis Expressions)** – KPI & measure calculations  
- **Excel** – Initial data validation  

---

## 📂 Dataset Overview

The dataset contains transaction-level details on car sales, including:

- `Car ID`, `Brand`, `Model`, `Body Style`, `Color`, `Engine Size`, `Transmission`
- `Price ($)`, `Units Sold`, `Date of Sale`
- `Region`, `Dealer Name`, `Customer Name`

---

## 📊 Key KPIs Calculated

| KPI                      | Description                           |
|--------------------------|----------------------------------------|
| 💰 **YTD Total Sales**         | Total revenue from car sales YTD |
| 📅 **MTD Sales**               | Monthly sales revenue |
| 🚘 **YTD Units Sold**          | Total car units sold YTD |
| 📈 **YoY Growth %**            | Year-over-Year growth vs last year |
| 💵 **YTD Avg Selling Price**   | Avg price per unit sold |
| 🔺 **Sales Difference**        | Difference in sales from last year |

DAX functions used: `TOTALYTD()`, `TOTALMTD()`, `SAMEPERIODLASTYEAR()`, `DIVIDE()`

---

## 📌 Business Questions Answered

- Which car brands generate the most sales?
- Which body styles and colors are most preferred?
- Which regions have the highest car sales?
- What are the average price and units sold per brand?
- What are weekly sales trends telling us?


---

## 💡 Key Insights

✅ **YTD Sales** reached **$371.2M** with **+23.59% YoY growth**  
✅ **13.3K cars sold**, with peak weeks showing **$14M+** sales volume  
✅ **SUVs** dominate the market with **26.9% share**  
✅ **Pale White** is the top-selling color; however, **100% of high-value cars** were sold in **Black**  
✅ **Chevrolet** and **Ford** are high-Revenue Company  
✅ **Hatfield Volkswagen** emerged as the leading dealership in sales  

---

## 🧹 Data Cleaning Performed

- Handled missing values in `Price`, `Color`, and `Engine Size`
- Standardized brand and body style names (e.g., "Suv" → "SUV")
- Extracted Date columns and created a Calendar Table for Time Intelligence
- Created custom columns for Price Segments and YoY comparison

---
![Dashboard_1](https://github.com/user-attachments/assets/b853d1da-1769-465a-9ce3-81f9c1e6b9b4)

![Dashboard_2](https://github.com/user-attachments/assets/cc17c7a6-b4d5-4382-8ec3-8de482c272cf)

## 📈 Dashboard Features

- Interactive filters by **Transmission**, **Dealer_Name**, **Body Style**, and **Engine**
- Dynamic KPI cards with color indicators for YoY performance
- Time-series trend for weekly sales
- Donut charts for car colors and body style share
- Bar charts for brand sales, average price, and units sold
- High-value car detail view with top dealers and luxury models

---

## 📌 Project Outcome

This dashboard supports:
- Strategic dealership expansion
- Optimized stock management for in-demand models and colors
- Data-backed marketing decisions by region and season
- Visibility into customer preferences in pricing and car design

---

## 👩‍💻 Author

**Riya Nemade**  
Aspiring Data Analyst | Power BI Enthusiast   

---

## 📎 Files Included

- `car_sales_analysis.pptx` – Final presentation  
- `Dashboard_1.png` – Dashboard Overview
- `Dashboard_2.png` -Dashboard Detail 
- `README.md` – Readme File  
- `car_sales.pbix` – Power BI Dashboard



