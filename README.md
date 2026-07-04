# 📊 AtliQ Hardware – Business Insights 360 | Power BI

 An end-to-end Business Intelligence solution built with Power BI to deliver a 360° view of AtliQ Hardware's performance across Finance, Sales, Marketing, Supply Chain, and Executive Management.

## 🌐 Live Demo

* Power BI Service:https://app.powerbi.com/view?r=eyJrIjoiZTg1MGNlZmMtYTY0NC00YmVlLTkwMjAtM2MzMTc2NDUxMDRkIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

---

# 📌 Project Overview

This project simulates a real-world enterprise Business Intelligence solution for **AtliQ Hardware** It transforms raw business data into interactive dashboards, enabling stakeholders to monitor KPIs, analyze profitability, evaluate forecasts, and make data-driven decisions.

---

# 🎯 Business Objectives

* Build department-specific dashboards.
* Monitor KPIs across Finance, Sales, Marketing, and Supply Chain.
* Analyze revenue, profitability, and forecast accuracy.
* Simulate real-world BI development with UAT and stakeholder feedback.

---

📁 **Dashboard Views & Insights** 

📊 Power BI Dashboard – Views & Insights

🏠 1. Home View

Central navigation landing page designed for smooth report browsing.
Features:
Section-wise navigation buttons for each dashboard (Finance, Sales, Marketing, Supply Chain, Executive)
Bookmark-based Info & Support tabs
Dataset overview + schema explanation for better user understanding

💰 2. Finance View

Focus: Overall financial performance, profitability, and P&L analysis
Visuals Used:
KPI Cards (Net Sales, Gross Margin %, Net Profit %)
→ With conditional formatting vs Target & LY
Full P&L Matrix (Current Year, LY, Target, % Change)
Top/Bottom Products & Customers (Profitability view)
Area Chart for trend analysis over time

Key Insights:
Net Sales grew strongly (~140%–354%) from 2019 to 2022
Despite revenue growth, Net Profit turned negative after 2019
Reason: rising OpEx due to aggressive expansion strategy

📈 3. Sales View

Focus: Customer behavior, product performance, and revenue breakdown
Visuals Used:
Scatter Chart: Net Sales vs Gross Margin % (toggle-enabled)
Donut Charts:
Net Sales share
Gross Margin distribution
COGS & deduction breakdown
Matrix: Customer & Product-level performance

Key Insights:
Notebook category led sales with 42.5% share (2022)
Amazon was top customer with ~$496.88M Net Sales
Relief segment showed relatively better Gross Margin efficiency

📢 4. Marketing View

Focus: Profitability vs marketing performance across segments
Visuals Used
Scatter Chart: GM% / NP% vs Net Sales (toggle switch)
Waterfall Chart: GM → OpEx → Net Profit flow
Pie Chart: GM% vs COGS contribution
Matrix: Segment & Market-wise performance

Key Insights:

All regions showed negative profitability in 2022
Main reason: Operational Expenses > Gross Margin
Marketing spend efficiency needs optimization

🚚 5. Supply Chain View

Focus: Forecast accuracy & demand planning performance
Visuals Used:
KPI Cards:
Forecast Accuracy %
Net Error
Absolute Error
Matrix: Customer & Product-wise forecast analysis
Line/Column Charts for trend tracking

Key Insights:
Dec 2021 recorded highest forecast deviation
FY2021 had highest absolute error (~$10M)
Forecast accuracy stabilized around 81.5%

🧑‍💼 6. Executive View

Focus: High-level business overview for leadership
Visuals Used:
KPI Cards with growth indicators
Multi-year trend charts (line, column, ribbon, area)
Sub-region performance breakdown
Top/Bottom customers & products matrix
Key Insights:
Retail segment contributed ~70.5% revenue
P&A division contributed ~49.9% share
Despite losses, market share grew to ~6% by 2022

ℹ️ 7. Info View

Provides a complete overview of the dashboard structure and available business domains.

**Features:**
- Introduction to the Business Insights 360 dashboard
- Overview of Finance, Sales, Marketing, Supply Chain, and Executive modules
- Summary of KPIs and analytical capabilities
- Helps users understand the report flow before exploring individual dashboards

🛠️ 8. Support View

Dedicated support page for users and contributors.

**Features:**
- Dashboard author and contact information
- LinkedIn and GitHub portfolio links
- Email for feedback, suggestions, and collaboration
- Microsoft Learn Power BI resources for beginners
- Easy access to learning materials and project support

---
# 🛠 Tech Stack

* Power BI Desktop
* SQL (MySQL)
* Power Query
* DAX
* Microsoft Excel
* DAX Studio
* Power BI Service

---

# 🏗 Data Modeling

* Snowflake Schema
* Fact & Dimension Tables
* Fiscal Date Table
* One-to-Many Relationships
* Data Validation (UAT)

---

# 📐 DAX Highlights

Developed **25+ business measures** including:

* Net Sales
* Gross Margin
* Net Profit
* Forecast Accuracy
* Revenue Contribution
* Dynamic Titles
* KPI Measures
* Target vs Last Year
* YTD & YTG Analysis

**Key Functions:** CALCULATE, SUMX, DIVIDE, SWITCH, VAR, SELECTEDVALUE, HASONEVALUE, SAMEPERIODLASTYEAR, ALL, ALLEXCEPT.

---

# 🚀 Performance Optimization

* Optimized Snowflake Data Model
* Reduced Calculated Columns
* Measure-Based Calculations
* Power Query Optimization
* DAX Studio Performance Tuning

---
# 💡 Business Impact

- Enabled 360° visibility of business performance
- Identified loss-making regions and cost drivers
- Improved forecast accuracy monitoring
- Helped identify top-performing customers & products
- Supported data-driven decision-making for leadership

---

# 🙏 Acknowledgements

Inspired by the **Codebasics Power BI Course**.

Special thanks to **Dhaval Patel**, **Hemanand Vadivel**, and the Codebasics team for their guidance.

---

