<!-- Hero Section with Images -->
<p align="center">
  <img src="https://github.com/ibrahim22-11/Supply-Chain-Logistics-/blob/main/Overview.png?raw=true" alt="Supply Chain Dashboard Overview" width="800">
</p>
<p align="center">
  <img src="https://github.com/ibrahim22-11/Supply-Chain-Logistics-/blob/main/Mfg%20and%20Transportation%20Dashboard.png?raw=true" alt="Manufacturing and Transportation Dashboard" width="390">
  <img src="https://github.com/ibrahim22-11/Supply-Chain-Logistics-/blob/main/Products%20Dashboard.png?raw=true" alt="Products Dashboard" width="390">
</p>

# 📦 **Supply Chain Logistics Dashboard**  

_A Complete Power BI + DAX Project by **Ibrahim** — Completed **Sept 1, 2025**_

---

## 📅 **Project Snapshot**
- **Start Date:** 25 August 2025  
- **Completion Date:** 1 September 2025  
- **Author:** Ibrahim (Aspiring Data Analyst)  

---

## 📊 **Key Performance Indicators**

| KPI                       | Value (Example) |
|--------------------------|----------------|
| **Total Revenue**         | 2.29 M |
| **Total Product Produced**| 57 K |
| **Total Product Sold**    | 46 K |
| **Total Product Available**| *(calculated dynamically)* |
| **Total Stock**           | 5 K |
| **Total Profit**          | *(calculated dynamically)* |
| **Average Profit**        | *(calculated dynamically)* |
| **Total Cost**            | *(calculated dynamically)* |
| **Manufacturing Cost**    | 5 K |
| **Transportation Cost**   | 53 K |
| **Defective Products**    | 6 K |

---

## 🧮 **DAX Measures**

```dax
Average Profit = AVERAGE('Sales'[Profit])
Defective Product = SUM('Sales'[Defective Units])
Mfg cost = SUM('Manufacturing'[Cost])
Total Cost = [Mfg cost] + [transportation cost]
Total Product Available = SUM('Inventory'[Available Units])
total Product Produced = SUM('Production'[Produced Units])
Total Product Sold = SUM('Sales'[Sold Units])
Total Profit = SUM('Sales'[Profit])
Total Revenue = SUM('Sales'[Revenue])
total Stock = SUM('Inventory'[Stock Units])
transportation cost = SUM('Transport'[Cost])




# 🧹 DATA CLEANING & PREPARATION
+ Performed data cleaning using Power Query
+ Removed duplicates, handled missing values, standardized dates
+ Built a star schema model with Fact & Dimension tables

# 📈 DASHBOARD VISUALIZATIONS
+ Overview Dashboard → High-level KPIs, city-wise revenue, transport mode revenue
+ Manufacturing & Transportation → Route-wise manufacturing cost, transport breakdown
+ Products Dashboard → SKU production, sales, inventory, profit by demographics

# 📂 ACCESS FULL PROJECT
+ 📄 PDF: [Click to View/Download](https://github.com/ibrahim22-11/Supply-Chain-Logistics-/raw/main/dashboards%20supply%20chain.pdf)
+ 🎥 Video Walkthrough: [Watch Dashboard Recording](https://github.com/ibrahim22-11/Supply-Chain-Logistics-/raw/main/supplychain%20Recording%20.mp4)

# 📚 PROJECT NARRATIVE & INSIGHTS
+ Context: Unified dashboard for supply chain monitoring across cities, suppliers, SKUs, transport modes.
+ Key Insights:
  - Kolkata is highest revenue-generating location
  - Route C has lowest manufacturing cost per unit
  - Rail transport is most profitable transport mode
  - High-demand SKUs dominate stock and sales
  - Demographic trends highlight product preferences

+ Business Impact:
  - Focus on Kolkata → better ROI
  - Shift more shipments to rail → cost savings
  - Prioritize top SKUs → better inventory turnover
  - Target promotions by demographics → more engagement

+ Process:
  1. Data cleaning & modeling using Power Query
  2. KPI creation with DAX
  3. Visualization with dark-themed Power BI dashboards
  4. Storytelling & insights generation

+ Challenges:
  - Handling missing data with calculated DAX measures
  - Maintaining clarity in a dark-themed design
  - Balancing interactivity with visual simplicity

+ Next Steps:
  - Automate refresh with Power BI Gateway
  - Add forecasting for demand & stock
  - Create alerts for stock-outs & defect rates

# 👨‍💻 ABOUT THE AUTHOR
+ Author: Ibrahim — Aspiring Data Analyst
+ Project Duration: 25 Aug – 1 Sept 2025
+ Skills Showcased: Power Query, DAX, Power BI, Data Cleaning, Storytelling
+ ✅ Project Successfully Completed on Sept 1, 2025
