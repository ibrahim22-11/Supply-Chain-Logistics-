# Supply-Chain-Logistics-


# **Supply Chain Logistics Dashboard**  
_A Power BI + DAX project by Ibrahim, Aspiring Data Analyst — Aug 25 to Sept 1_

---

##  Project Snapshot & Timeline  
- **Date Range:** August 25 – September 1  
- **Analyst:** Ibrahim (Aspiring Data Analyst)  
- **Objective:** Build an end-to-end interactive dashboard in Power BI to monitor supply chain KPIs, product performance, cost and revenue breakdowns, and demographic insights.

---

##  Key Performance Indicators (Aggregated View)

| Metric                  | Value     |
|------------------------|-----------|
| **Total Revenue**       | 2.29 M    |
| **Total Product**       | 57 K      |
| **Total Sold**          | 46 K      |
| **Total Stock**         | 5 K       |
| **Total Profit**        | (add value) |
| **Total Cost**          | (add value) |
| **Transportation Cost** | 53 K      |
| **Manufacturing Cost**  | 5 K       |
| **Defective Products**  | 6 K       |

---

##  Visual Dashboard Overview (Dark-Mode)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="overview-dark.png">
  <img alt="Overview of KPIs and charts: location revenue, route costs, transport mode revenue" src="overview-light.png">
</picture>

A unified visual that highlights top-line metrics, geographical revenue trends, cost by manufacturing route, and transport mode performance.

---

##  Product & SKU-Level Insights

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="products-dark.png">
  <img alt="SKU-level bar charts for production, sales, and stock" src="products-light.png">
</picture>

Includes:
- Product produced by SKU
- Product sold by SKU
- Stock levels per SKU
- Profit by demographic
- Category scatter plot

---

##  Revenue & Profit Breakdown

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="profit-dark.png">
  <img alt="Profit by demographics; revenue by product type, supplier, and carrier" src="profit-light.png">
</picture>

Breaks down profit by demographic segments, revenue by product category, carrier, and supplier.

---

##  Data Workflow & Technical Architecture

**1. Data Cleaning & Transformation (Power Query)**  
- Imported raw data from CSV/DB.  
- Cleaned and standardized dates, removed duplicates, fixed missing values.  
- Structured tables and relationships for efficient modeling.

**2. DAX Measures (Power BI)**  
Examples:
```dax
OnTimePercent = DIVIDE([On Time Deliveries], [Total Deliveries])
InventoryTurnover = DIVIDE([Total Sold], [Average Stock])
ProfitMargin = DIVIDE([Total Profit], [Total Revenue])
