# 🛒 Retail Inventory Optimization Dashboard

A data-driven Power BI dashboard built to visualize and analyze product sales, supplier performance, inventory levels, and category-wise contribution in a retail business.

## 📊 Project Overview

This dashboard helps retailers gain critical insights into:

- 📦 Product performance (Units Sold vs Target)
- 🧾 Inventory status (Reorder Levels, Stock Available)
- 📈 Time-based sales trends (Year → Month → Day)
- 👑 Top performing products and underperformers
- 📊 Category-wise contribution to sales

## 🛠️ Tools & Tech
- **Power BI** for dashboard creation and data visualization  
- **Microsoft Excel** for data storage and import  
- **DAX (Data Analysis Expressions)** for calculated columns and measures

## 📂 Dataset

The dataset includes:
- `Product_Name`
- `Category`
- `Supplier_Name`
- `Units_Sold`
- `Stock_Available`
- `Reorder_Level`
- `Lead_Time`
- `Order_Date`

Custom DAX fields created:
- `Target_Units` – a calculated field based on stock and performance expectations.

## 🔍 Key Visuals in the Dashboard

| Visual Type              | Description                                                  |
|--------------------------|--------------------------------------------------------------|
| KPI Cards                | Key stats like Total Units Sold, Avg Lead Time, etc.         |
| Donut Chart              | % Contribution of Units Sold by Category                     |
| Pie Chart                | Reorder Level by Product                                     |
| Bar Charts               | Top 3 Products, Units Sold by Category, Target vs Actual     |
| Line Graph               | Sales Trend (Year → Month → Day)                             |
| Max Visual               | Highest performing product in each category                  |
| 100% Stacked Bar         | Sales contribution % by Category                             |
| Filters                  | Top N, Category-wise Drilldowns, Supplier-wise comparisons   |

## 🎯 Insights You Can Gain

- Identify top-performing and lowest-selling products
- Monitor real-time stock vs reorder thresholds
- Track supplier efficiency through lead time visuals
- Understand which categories dominate revenue
- Reveal trends in daily/weekly/monthly sales patterns

## 🎨 Theme & Design

- Background: Soft pink for a clean, feminine aesthetic 🌸
- Visual spacing for clarity and balance
- Styled titles and labels for maximum readability

## 💖 Created By

**Priya Sharma**  
---

