# Excel Sales Dashboard Project

## Project Overview

This project is a comprehensive **Excel Sales Dashboard** designed for analyzing and visualizing sales, profit, discounts, customers, and product performance data. The dashboards are built entirely using **Pivot Tables, Pivot Charts, Calculated Fields, and Slicers** for dynamic and interactive insights.

The dataset contains over 2,500 records and 18 columns including:

* OrderDate, Region, City
* CustomerName, CustomerSegment
* ProductName, Category, SubCategory
* Channel, PaymentMethod, OrderStatus, ShippingDays
* UnitPrice, Quantity, Discount, TotalSales, Profit
* UnitCost, TaxRate

This dashboard is ideal for business analysts and managers to understand sales trends, profitability, customer behavior, and operational performance.

## Dashboards

### Dashboard 1: Operational Insights

1. **Profit vs Cost by Category (Clustered Column Chart)**
2. **Sales by Region (Column Chart)**
3. **Top 10 Products (Bar Chart)**
4. **Sales by Channel (Pie Chart)**
5. **Discount Impact on Profit (Line Chart)**

### Dashboard 2: Advanced Analytics

1. **Monthly Sales Trend (Line Chart)**
2. **Customer Segment Performance (Combo Chart: Column + Line)**
3. **Sales by region (Clustered Column Chart)**
4. **Profit margin by region (barh Chart)**

## Features

* **Dynamic Pivot Tables:** All charts are linked to pivot tables for automatic updates when new data is added.
* **Calculated Fields:** Example: `Profit Margin = Profit / TotalSales`.
* **Interactive Slicers:** Filter dashboards by Region, Category, Customer Segment, and Channel.
* **Conditional Formatting & Colors:** charts are color-coded for quick insights.
* **Supports New Data:** Simply paste new records into the table and refresh all pivot tables for updated dashboards.

## How to Use

1. Open `SalesData.xlsx`.
2. Navigate to the Dashboard worksheet.
3. Use the **Slicers** to filter data dynamically.
4. Add new data to the dataset and click **PivotTable Analyze → Refresh All** to update all charts.
5. All trends, and visualizations will automatically adjust.

## Technologies Used

* Microsoft Excel 2016+ (Pivot Tables, Pivot Charts, Slicers, Calculated Fields)
* Conditional Formatting for charts
* 
## Notes

* Ensure that the dataset table is formatted as a **Table** in Excel so that all new rows are automatically recognized.
* Charts are best viewed in **Full Screen / Large Monitor** for clarity.
* Maintain column names exactly as provided to ensure all pivot tables and calculated fields work correctly.

## Author
Ahmed Amer
