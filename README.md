# ECommerce-Sales-Insights-Dashboard
# E-Commerce Sales & Customer Insights Dashboard

## 📌 Project Overview
This project focuses on analyzing retail sales data for the year 2025 to extract key performance indicators (KPIs) regarding profitability, customer behavior, and regional sales performance. The goal is to provide corporate stakeholders with actionable insights to optimize sales strategies.

## 🛠️ Tech Stack & Skills
*   **BI Tool:** Power BI Desktop
*   **Data Source:** Excel Dataset (1,500+ rows of transactions)
*   **Languages:** DAX (Data Analysis Expressions)
*   **Key Concepts:** KPI Cards, Time-Series Analysis, Product Segmentation.

## 📈 Key Metrics & DAX Measures Used
1.  **Total Sales:** `SUM(SalesData[Sales])` - Tracks the absolute revenue generated.
2.  **Total Profit:** `SUM(SalesData[Sales]) - SUM(SalesData[Cost])` - Calculates net profitability.
3.  **Profit Margin %:** `DIVIDE([Total Profit], SUM(SalesData[Sales]), 0)` - Formatted as percentage to evaluate financial efficiency.

## 💡 Key Business Insights
*   The business operates with a solid **23.28% Gross Profit Margin**.
*   **Technology** and **Furniture** drive the highest volume of high-value sales.
*   The interactive line chart clearly identifies seasonality and peak purchasing weeks throughout the fiscal year.
