<!-- Visual Header -->
<p align="center">
  <img src="your-dashboard-dark.png" alt="Dark-themed Supply Chain Dashboard overview" />
</p>

# **Supply Chain Logistics Dashboard**  
_A Power BI + DAX project by Ibrahim, Aspiring Data Analyst — Aug 25 to Sept 1_

---

##  Project Snapshot & Timeline  
- **Date Range:** August 25 – September 1  
- **Analyst:** Ibrahim (Aspiring Data Analyst)  
- **Objective:** Build an interactive dashboard to monitor supply chain KPIs, product performance, costs, and revenue—delivered with clean data, robust modeling, and compelling visuals.

---

##  Key Performance Indicators

| Metric                  | Value  |
|-------------------------|--------|
| **Total Revenue**        | 2.29 M |
| **Total Product**        | 57 K   |
| **Total Sold**           | 46 K   |
| **Total Stock**          | 5 K    |
| **Transportation Cost**  | 53 K   |
| **Manufacturing Cost**   | 5 K    |
| **Defective Products**   | 6 K    |
| **Total Profit / Cost**  | *(add your values)* |

---

##  Dashboard Overview (Dark-Mode Optimized)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="overview-dark.png">
  <img alt="Combined KPI overview: revenue, costs, product and transport charts" src="overview-light.png">
</picture>

This unified visual displays all your dashboards (KPIs, location revenues, route costs, transport mode analysis) together—designed with a dark-background aesthetic that highlights data clarity and visual prominence.

---

##  Product & SKU Insights

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="products-dark.png">
  <img alt="SKU-level insights: production, sales, stock" src="products-light.png">
</picture>

Visuals include:
- Product produced, sold, and stock levels by SKU
- Profit distributions by demographic
- Product category scatter plot (cosmetics, haircare, skincare)

---

##  Revenue & Profit Breakdown

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="profit-dark.png">
  <img alt="Profit by demographics; revenue by category, carrier, supplier" src="profit-light.png">
</picture>

Features:
- Profit segmentation by demographic groups
- Revenue by product type, carrier, and supplier
- Dynamic table listing of SKU revenue

---

##  Data Workflow & Technical Architecture

**1. Data Cleaning & Power Query**  
- Imported raw data (CSV/DB), cleaned dates, handled duplicates/missing entries.  
- Structured relationships and optimized model for analytics.

**2. DAX Measures (Key Examples):**
```dax
OnTimePercent = DIVIDE([On Time Deliveries], [Total Deliveries])
InventoryTurnover = DIVIDE([Total Sold], [Average Stock])
ProfitMargin = DIVIDE([Total Profit], [Total Revenue])
