<!-- Visual Header – Combined Dashboards Showcase -->
<p align="center">
  <img src="https://github.com/ibrahim22-11/Supply-Chain-Logistics-/blob/main/Overview.png?raw=true" alt="Supply Chain Dashboard Overview" width="400" />
  <img src="https://github.com/ibrahim22-11/Supply-Chain-Logistics-/blob/main/Mfg%20and%20Transportation%20Dashboard.png?raw=true" alt="Manufacturing and Transportation Dashboard" width="400" />
  <img src="https://github.com/ibrahim22-11/Supply-Chain-Logistics-/blob/main/Products%20Dashboard.png?raw=true" alt="Products Dashboard" width="400" />
</p>

# **Supply Chain Logistics Dashboard**  
_A Power BI & DAX project by Ibrahim — Completed Sept 1_

---

##  Project Snapshot & Timeline  
- **Date Range:** August 25 – September 1  
- **Analyst:** Ibrahim (Aspiring Data Analyst)  
- **Objective:** Develop an all-in-one, dark-mode-ready dashboard in Power BI for tracking supply chain KPIs, including production, cost, SKU-level performance, and transport analytics.

---

##  Key Performance Indicators (Unified View)

| Metric                  | Value     |
|-------------------------|-----------|
| **Total Revenue**        | 2.29 M    |
| **Total Product (Produced)** | 57 K      |
| **Total Sold**           | 46 K      |
| **Total Stock**          | 5 K       |
| **Transportation Cost**  | 53 K      |
| **Manufacturing Cost**   | 5 K       |
| **Defective Products**   | 6 K       |
| **Total Profit / Cost**  | *(please add your value)*

---

##  Embedded Dashboards Overview

### Overview & Combined KPIs
Displays top-line figures—including location revenue, cost breakdown, mode-wise transport revenues, and core metrics (Revenue, Product, Stock, etc.).

### Manufacturing & Transportation
Highlights cost distribution by routes (A, B, C), transport mode revenue, and manufacturing-related insights.

### Products Dashboard
Gives SKU-level visibility—from production and sales to inventory and profit—and includes category and demographic breakdowns.

---

##  Dashboard PDF & Recording

- **Comprehensive PDF Overview:**  
  [View the full dashboard as pdf]((https://github.com/ibrahim22-11/Supply-Chain-Logistics-/blob/main/dashboards%20supply%20chain.pdf?raw=true))

- **Interactive Walkthrough (Video):**  
  [Watch the dashboard in action]((https://github.com/ibrahim22-11/Supply-Chain-Logistics-/blob/main/supplychain%20Recording%20.mp4?raw=true))

---

##  Data Workflow & Technical Architecture

**1. Data Cleaning & ETL (Power Query)**  
- Imported raw datasets via Power Query  
- Standardized date formats, removed duplicates, handled missing data  
- Structured tables with relationships for efficient modeling

**2. Modeling & DAX Calculations**  
Sample measures:
```dax
OnTimePercent = DIVIDE([On Time Deliveries], [Total Deliveries])
InventoryTurnover = DIVIDE([Total Sold], [Average Stock])
ProfitMargin = DIVIDE([Total Profit], [Total Revenue])
