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
<img width="1204" height="710" alt="{3FB2848F-790E-48F1-88BF-F3297E92F82D}" src="https://github.com/user-attachments/assets/c0f122c4-5eea-45b3-a0ab-aa89902f4038" />


<img width="1148" height="637" alt="{8B4AD3AA-26C8-4137-A6F8-6FEB5CAEFDF9}" src="https://github.com/user-attachments/assets/143fc61b-ea9b-4da3-879a-28e359abdbd7" />

<img width="970" height="614" alt="{5C0CD087-A11C-47A9-AC24-0A7745ABD7F6}" src="https://github.com/user-attachments/assets/406c3dfa-de91-4a13-94f1-07119d78715a" />



---

## 📈 Dashboard Features
- KPI scorecards for quick performance overview  
- Time-series charts for sales trends  
- Bar charts and pie charts for product and category performance  
- Geographic analysis by state  
- Interactive filters:
  - Date  
  - Category  
  - Product  
  - State  

---

## 💡 Key Insights

- **Sales Performance:**  
  Total revenue reached **$8.13K** across **962 orders**.  
  The **Average Order Value ($8.45)** and **average order size (2.4 units)** are relatively low, indicating strong **upsell opportunities**.

- **Category Performance:**  
  Sales are almost evenly split between **Coffee (50.4%)** and **Tea (49.6%)**, creating ideal conditions for **cross-category promotions and bundle strategies**.

- **Product Performance:**  
  **Mystic Oolong** is the top-performing product with **1.8K units sold**, clearly leading the market.  
  The **top 3 products** contribute a significant share of total sales, highlighting **sales concentration risk**.

- **Geographic Performance:**  
  **Georgia, Texas, and North Carolina** generate the highest sales.  
  **Michigan and New York** underperform, suggesting potential **marketing, distribution, or demand issues**.

- **Seasonal Trends:**  
  A clear sales peak occurs in **December**, driven by the **holiday effect**.  
  **September** records the lowest sales, indicating seasonal demand decline.  
  A sharp increase from **November to December** emphasizes the importance of **pre-holiday planning**.


---

## 📌 Business Recommendations

### 🚀 Short-Term (Immediate)
- Bundle Mystic Oolong with low-performing tea products to boost overall sales
- Run short-term promotional campaigns around the Top 3 best-selling products
- Launch localized marketing initiatives (discounts, free shipping) for Michigan and New York

### 📈 Medium-Term
- Expand the Oolong tea product line with new flavors or premium versions
- Introduce Coffee & Tea combo or pairing products to encourage cross-selling
- Increase Average Order Value (AOV) through checkout-level upsell offers

### 🧠 Long-Term
- Conduct deeper customer profiling in high-performing states
- Use seasonal trends for inventory planning and demand forecasting
- Implement a loyalty program to increase repeat purchases

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

