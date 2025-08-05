# Superstore-analysis
The Superstore Sales dataset is a fictional but widely used sample representing order transactions across the U.S. It includes data on sales, profits, customers, shipping, and products. This dataset enables meaningful insights into business performance at different levels monthly trends, customer segments, shipping preferences.
# 🛒 Superstore Sales Dashboard

This repository contains an interactive and insightful **Sales Performance Dashboard** built from the popular **Superstore Dataset**. The dashboard was created to track, analyze, and visualize key performance indicators across Sales, Profit, Discounts, Shipments, and Regional Performance.

## 📌 Project Objective

To transform raw transactional sales data into meaningful business intelligence through effective data cleaning, analysis, and visual storytelling. The dashboard is intended to help business stakeholders make informed decisions on:

- Top-performing products and categories
- Regional sales performance
- Profitability and discount trends
- Shipping modes and delivery impact

## 🧾 Dataset Overview

The dataset used is the Sample Superstore data, which includes:

- **Orders**: Order ID, Order Date, Ship Date, Ship Mode
- **Products**: Product Name, Category, Sub-Category
- **Sales Data**: Sales, Quantity, Discount, Profit
- **Customers**: Customer Name, Segment
- **Geography**: State, Region, Country

> 📂 File used: `Sample - Superstore.csv`

## 🔍 Data Cleaning & Preprocessing

Performed using Power Query / Excel / Python:
- Removed missing and duplicate values
- Parsed dates and calculated delivery duration
- Standardized categorical fields
- Created custom columns (e.g. Profit Ratio, Days to Ship)

## 📊 Dashboard Highlights

### ✅ Key Features:
- **Sales & Profit Overview:** Track total sales, profit, and average discount over time.
- **Top Categories & Sub-Categories:** Identify which product lines drive the most value.
- **Region-wise Performance:** Compare sales, profit, and order counts by region/state.
- **Shipping Analysis:** Evaluate the efficiency and impact of different shipping modes.
- **Dynamic Filters:** Drill down by Segment, Category, Region, and Date range.

### 📷 Sample Visualization
![Dashboard Screenshot](https://github.com/EjiroGee/Superstore-analysis/blob/main/super%20store%20analysis%20jpeg.jpg)

## 💡 Key Insights
- The **West Region** consistently outperforms in both sales and profit.
- **Furniture** often has high discounts but generates lower profit margins.
- **Second Class Shipping** has the slowest delivery and affects customer satisfaction.
- High **Discounts** do not always correlate with higher sales volume or profit.

## 🚀 Tools & Technologies

| Tool          | Purpose                        |
|---------------|--------------------------------|
| Excel         | Data cleaning and validation, Data visualization and modeling  | 

## 📁 Repository Structure

```bash
├── Sample - Superstore.csv        # Raw dataset
├── Superstore Dashboard.xlsx      # Excel dashboard file
├── dashboard-screenshot.png       # Dashboard preview
├── README.md                      # This file
