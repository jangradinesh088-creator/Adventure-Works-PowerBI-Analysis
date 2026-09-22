# 📊 Adventure Works - End-to-End Business Intelligence & Sales Dashboard

## 📌 Project Overview
Developed an interactive, end-to-end Power BI report to track sales revenue ($24.9M+), product profitability, return rates, and customer demographics for a global manufacturing enterprise (Adventure Works).

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Tool:** Power BI Desktop & Power BI Service
* **ETL & Data Transformation:** Power Query (M Language)
* **Data Modeling:** Star Schema Architecture (1:Many Relationships)
* **Analytics & Calculations:** Advanced DAX (Time Intelligence, YTD, YoY Growth, Dynamic Ranking)
* **Data Visualization:** Multi-page Dashboards, Drill-Through Navigation, Dynamic Tooltips, Field Parameters

---

## 🏗️ Data Architecture & Pipeline
1. **Data Ingestion & Cleansing:** Handled missing values, updated data types, and created custom/conditional columns in Power Query.
2. **Data Modeling:** Designed an optimized **Star Schema** connecting Fact tables (`Sales`, `Returns`) with Dimension tables (`Customers`, `Products`, `Territories`, `Calendar`).
3. **DAX Measures Created:**
   * **Total Revenue:** `SUM(Sales[OrderQuantity] * Sales[UnitPrice])`
   * **Profit Margin %:** `DIVIDE([Total Profit], [Total Revenue], 0)`
   * **YoY Revenue Growth:** `CALCULATE([Total Revenue], SAMEPERIODLASTYEAR('Calendar'[Date]))`

---

## 📈 Dashboard Highlights & Pages
* **Executive Summary:** High-level operational health, core KPIs, revenue trends, and top-performing categories.
* **Product Detail Page:** Deep dive into product margins, inventory return rates, and item-level profitability.
* **Customer Insights:** Demographic segmentation, customer lifetime value (CLV), and ordering behavior analysis.
* **Regional Analysis:** Spatial mapping across global sales territories to pinpoint underperforming regions.

---

## 📸 Dashboard Screenshots
* **Executive Summary:** ![Alt text](https://github.com/jangradinesh088-creator/Adventure-Works-PowerBI-Analysis/blob/main/Home.PNG)
* **Product Detail Page:** ![Alt text](https://github.com/jangradinesh088-creator/Adventure-Works-PowerBI-Analysis/blob/main/Product%20detail.png)
* **Map / Regional Detail:** ![Alt text](https://github.com/jangradinesh088-creator/Adventure-Works-PowerBI-Analysis/blob/main/map.png)
* **Customer details:**  ![Alt text](https://github.com/jangradinesh088-creator/Adventure-Works-PowerBI-Analysis/blob/main/cdetails.png)

---

## 🚀 How to View the Project
1. Clone or download this repository.
2. Open `Adventure_Works_Dashboard.pbix` in **Power BI Desktop**.
