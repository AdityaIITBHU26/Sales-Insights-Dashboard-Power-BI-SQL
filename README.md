# Sales Insights Dashboard | Power BI & SQL

This project is a complete end-to-end analytics solution designed to analyze the sales performance of a computer hardware and peripherals business operating across multiple Indian markets. The goal was to transform raw transactional data into interactive, decision-driven visual insights that help leadership track revenue, profitability, customer contribution, and product performance.

The dashboard answers key business questions such as:
- *Which markets contribute the highest revenue and profit?*
- *Which products and customers drive major sales?*
- *How is performance trending across years and months?*
- *Where are losses occurring and why?*

---

##  Problem Statement

The sales team lacked a structured analytical system, relying on manual spreadsheets that made trend analysis and performance tracking difficult. Decision-making was reactive due to fragmented reports, inconsistent currency formats, and no consolidated profit analysis.

To solve this, I built a unified Power BI dashboard that centralizes sales data and provides real-time, interactive business insights.

---

##  Project Objectives

- Build a scalable BI solution for sales monitoring
- Standardize multi-currency transactional data
- Model data using fact/dimension schema for optimized analytics
- Track KPIs such as Revenue, Sales Quantity, Profit Margin, Contribution %, Customer Ranking
- Enable data-driven decision making through intuitive dashboards

---

##  Tech Stack & Tools

| Task | Tools Used |
|------|------------|
| Data Storage | MySQL |
| ETL & Cleaning | Power Query |
| Data Modeling | Star Schema |
| Visualization | Power BI |
| KPI Logic | DAX Measures |

---

##  Data Processing Workflow

1. Extracted transactional data from MySQL
2. Cleaned and standardized currency values
3. Built custom product classifications (Own Brand vs Distribution)
4. Created calculated columns (Cost Price, Profit, Profit %)
5. Designed a star-schema data model for efficient querying
6. Created KPI measures for:
   - Total Revenue
   - Total Sales Quantity
   - Total Profit & Profit Margin %
   - Revenue & Profit Contribution %
7. Developed interactive dashboard visuals

---

##  Dashboard Highlights

### **KPI Overview**
- **₹985M total revenue across 4 years**
- **2M total sales quantity**
- Market-wise revenue comparison
- Top 5 products & top 5 customers breakdown
- Revenue trend across FY 2017–2020

### **Performance Insights**
- Monthly revenue vs last year comparison
- Profit margin trend analysis
- Region-wise contribution & profitability matrix
- Customer-level performance review

### **Profit Analysis**
- Revenue share vs profit share by market
- Loss-making regions highlighted (e.g., Bengaluru negative margins)
- Product-wise profit concentration

---

## Dashboard Screens

### **KPI Summary**
![KPI Dashboard](Screenshots/Sales-Insight-KPI.png)

### **Performance Insights**
![Performance Page](Screenshots/Sales-Insight-Performance.png)

### **Profit Analysis**
![Profit Page](Screenshots/Sales-Insight-Profit.png)


---

## 📈 Key Insights

| Category | Insight |
|----------|---------|
| Top Market (Revenue) | **Delhi NCR — ₹520M (52.8% contribution)** |
| Top Profit Market | **Bhubaneshwar — 10.5% margin** |
| Lowest Profit Market | **Bengaluru — -20.8% margin** |
| Best Customer | **Electricalsara Stores — ₹413M revenue** |
| Best Product | **Prod318 — ₹69M revenue** |
| Product Category Split | Distribution: **₹494M**, Own Brand: **₹491M** |

---

## 🔥 Key Learnings

- Built end-to-end BI pipeline from database to insights
- Improved skills in data modeling, validation, and cleansing
- Created reusable DAX functions and custom KPIs
- Designed business dashboards with storytelling UI/UX

---

## 📂 Repository Structure

📦 Sales-Insights-Dashboard
┣ 📂 SQL
┣ 📂 PowerBI_File
┣ 📂 Screenshots
┣ README.md


---

## 👤 Author

**Aditya Arun Gajbhiye**  
Data Analyst | BI & Analytics | SQL | Power BI   
IIT BHU VARANASI
adityagajbhiye77@gmail.com  
Maharashtra, India

---