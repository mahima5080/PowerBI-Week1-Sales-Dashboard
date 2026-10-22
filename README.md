# Power BI Week 1: Sales & Profitability Dashboard

This repository contains the completed **Week 1 Assignment** for the Power BI & Data Modelling module. The dashboard provides key insights into global sales performance, regional revenue distribution, and product profitability using Microsoft Power BI Desktop.

---

## 📊 Dashboard Preview

![Power BI Sales Dashboard](Dashboard_Screenshot.png)

---

## 📌 Key Insights & Metrics

- **Total Revenue:** **$118.73M** across all global segments and product lines.
- **Sales by Region:**
  1. **United States of America:** $25.03M
  2. **Canada:** $24.89M
  3. **France:** $24.35M
  4. **Germany:** $23.51M
  5. **Mexico:** $20.95M
- **Top 5 Products by Profit:**
  1. **Paseo:** $4.80M
  2. **VTT:** $3.03M
  3. **Amarilla:** $2.81M
  4. **Velo:** $2.31M
  5. **Montana:** $2.11M

---

## 🛠️ Data Transformation & Modelling Steps

1. **Power Query Cleaning:**
   - Imported raw financial data from Excel (`Sample data (1).xlsx`).
   - Cleaned column whitespace (` Sales` trimmed to `Sales`).
   - Verified data types across text, decimal, currency, and date fields.

2. **DAX Measures Implemented:**
   - **Total Revenue:** `Total Revenue = SUM(Sheet1[Sales])`
   - **Total Profit:** `Total Profit = SUM(Sheet1[Profit])`
   - **Total Units Sold:** `Total Units Sold = SUM(Sheet1[Units Sold])`

3. **Visualizations Configured:**
   - **KPI Card:** Displaying overall Total Revenue ($118.73M).
   - **Clustered Bar Chart:** Visualizing revenue breakdown by Country/Region.
   - **Top N Filtered Bar Chart:** Ranking the Top 5 Products by total profit generation.

---

## 📁 Repository Structure

```text
PowerBI-Week1-Sales-Dashboard/
├── PowerBI_Week1_Sales_Dashboard.pbix  # Main Power BI Desktop file
├── Sample data (1).xlsx                 # Source dataset
├── Dashboard_Screenshot.png             # Output dashboard image
└── README.md                            # Project documentation
