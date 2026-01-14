# 📊 PolicyBazaar Insurance Premium & Payout KPI Analytics – Power BI Dashboard
---
![PolicyBazaar Logo](PB-Logo.png)

---

## 📌 Project Overview
This project presents an interactive **Power BI insurance analytics dashboard** built using an AI-generated dataset inspired by PolicyBazaar, covering the period **2015–2025**. The report provides a single, unified view of the insurance business, enabling stakeholders to monitor policy performance, analyze premiums and payouts, assess maturity outcomes, and evaluate overall business growth.

> ⚠️ **Note:** This project is created for learning and portfolio purposes and does not use real PolicyBazaar data.

---

## 🎯 Business Goals
The primary objective of this project is to support **data-driven decision-making** across insurance operations by analyzing the complete policy lifecycle for active policies.

### Key Business Questions Addressed
- How are different insurance policy types performing across customer segments?  
- Which states and regions are overperforming or underperforming?  
- Which policy plans are top performers, and which have low customer uptake?  
- How efficiently are claims being settled, and where do bottlenecks exist?  
- How can sales, claims, and loan servicing teams be evaluated for accountability and performance?  

---

## 🗂️ Data Model

![Data Model](data_model.png)

## 🔗 Live Dashboard
[View Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOGVmZGNhY2ItOWIyNi00MTZhLTg2ODgtOTM3NjIyNDA0YmZhIiwidCI6IjE3ZDc5MTIxLTY4M2EtNDNlNS1iNTIwLWFjYTE5ZTc1MGU5OSJ9&pageName=f28a1e9e7a399c571eb0)

---
# 📊 Dashboard Features

## 📌 Executive Summary
Get a high-level snapshot of business performance with key insurance KPIs and overall health indicators.

## 📈 Insurance Performance Overview
Analyze premium, growth, ROI, and profitability across:
- Policy types  
- Customer segments  
- Regions  
- Time periods  

## 📊 Growth & Comparison Trends
Track policy growth patterns and compare performance trends across multiple dimensions and time periods.

## 💰 Premium & Maturity Analysis
Examine:
- Premium inflows  
- Maturity payouts  
- ROI trends  
- Profitability  

to assess overall financial performance.

## 🧩 Sales Hierarchy Performance
Evaluate performance across sales hierarchy levels, enabling visibility from:
- Zonal Managers  
- Regional Managers  
- Sales Agents  
- Policyholders
 
---
## 🗂️ Data Sources

- Snowflake: AI-generated insurance data(csv files) was loaded and stored in Snowflake tables.
- Power BI (Import Mode): Data was imported from Snowflake into Power BI, where the star schema data model was created for analysis and reporting.
- Time Span: 2015–2025 (active policies only)

---

## 📈 Key KPIs Tracked 
- Total Premium Amount  
- Total Annual Premium  
- Total Premium Paid
- Total Premium Payable  
- Maturity Amount  
- Annualized ROI (%)  
- Profit / Gain  
- Underwriting Expenses  
- CAGR (%) – Compound Annual Growth Rate  

---
## 🛠 Tools Used

- Microsoft Excel – Data preparation (CSV format)  
- Power BI – Data modeling, DAX, and dashboard visualization  
- Snowflake – Cloud data storage  

