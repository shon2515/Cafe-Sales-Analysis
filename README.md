# 📊 Cafe Sales Performance – Looker Studio Project

## 📌 Project Overview
This project analyzes sales transaction data stored in Google Sheets (CSV format) and visualized using Looker Studio to generate actionable business insights.  
The goal was to track sales performance, understand customer purchasing patterns, and evaluate product and category-level performance through an interactive dashboard.

---

## 🎯 Project Objectives
- Analyze overall sales performance and revenue trends  
- Calculate key business KPIs from transactional data  
- Analyze sales by product, category, and state  
- Build an interactive Looker Studio dashboard for decision-making  

---

## 🧰 Tools & Technologies
- **Google Sheets**
  - Data storage (CSV-based transactional data)
  - Data cleaning & preparation  
- **Looker Studio**
  - Data modeling
  - Calculated fields (KPIs)
  - Interactive dashboards & filters  

---

## 🗂 Dataset Description
The dataset consists of transactional sales data with the following fields:

- Order ID  
- Date  
- Product  
- Category  
- State  
- Units Sold  
- Unit Price  
- Sales  
<img width="1403" height="830" alt="{E27E3E8D-4157-446B-8F63-D0D5A5987BC7}" src="https://github.com/user-attachments/assets/d8b3312c-6e5d-4d7e-95b8-537d1b778b5b" />

---

## 🔄 Data Workflow
1. Sales data stored and maintained in Google Sheets  
2. Google Sheets connected directly to Looker Studio  
3. Looker Studio used to:
   - Create calculated fields  
   - Aggregate sales metrics  
   - Build visualizations and filters  
4. Dashboard automatically updates with changes in Google Sheets  

---

## 📐 KPI Calculations
- **Total Revenue:** `SUM(Sales)`  
- **Total Orders:** `COUNT_DISTINCT(Order ID)`  
- **Total Units Sold:** `SUM(Units Sold)`  
- **Average Order Value (AOV):**  
  `SUM(Sales) / COUNT_DISTINCT(Order ID)`  
- **Average Units per Order:**  
  `SUM(Units Sold) / COUNT_DISTINCT(Order ID)`  

---

## 📊 Dashboard Analysis
- Sales trends over time  
- Product and category-level performance  
- Geographic sales analysis by state  

---

## 📈 Dashboard Features
- KPI scorecards for quick performance overview  
- Time-series charts for sales trends  
- Bar charts for product and category performance  
- Geographic analysis by state  
- Interactive filters:
  - Date  
  - Category  
  - Product  
  - State  

---

## 💡 Key Insights
- Sales are driven primarily by a small number of top-performing products  
- Certain categories contribute a significant share of total revenue  
- Strong regional differences in sales performance across states  
- Average units per order indicate opportunities for upselling  

---

## 📌 Business Recommendations
- Focus marketing efforts on high-performing products and regions  
- Optimize inventory planning based on category demand  
- Use regional insights to design targeted promotions  
- Continuously monitor sales performance using the dashboard  

---

## ✅ Skills Demonstrated
- Data modeling using Google Sheets  
- KPI creation in Looker Studio  
- Interactive dashboard design  
- Sales performance analysis  
- Translating raw data into actionable insights  

---

## 📌 Project Outcome
This project demonstrates my ability to connect live data sources to Looker Studio, design interactive dashboards, and deliver data-driven insights for business stakeholders.

