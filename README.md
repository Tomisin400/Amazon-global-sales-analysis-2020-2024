

# 🔍 I Audited Amazon's 100,000 Sales Transactions — Here's What Nobody Is Talking About

Most sales reports tell you what happened.
This analysis tells you what Amazon should be worried about.

After analyzing 100,000 Amazon sales transactions across 5 
countries and 5 years, I uncovered a silent revenue decline, 
a $5.6M revenue leakage hiding in plain sight, and a market 
concentration risk that threatens long-term business stability. 
This is not a reporting project,this is a business intervention.



## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Dataset](#-dataset)
- [Data Cleaning Process](#-data-cleaning-process)
- [Analysis Approach](#-analysis-approach)
- [Dashboard](#-dashboard)
- [Key Findings](#-key-findings)
- [Insights](#-insights)
- [Recommendations](#-recommendations)
- [Tools Used](#tools-used)
- [About the Analyst](#about-the-analyst)



## 📊 Project Overview

This project is a comprehensive end-to-end sales performance 
analysis of Amazon's global transactions from 2020 to 2024. 
Starting from 100,000 rows of raw data and ending with a fully 
interactive Excel dashboard, this analysis was built around one 
central business question:

> "Is Amazon's sales performance as healthy as the numbers 
suggest? and if not, where exactly is the problem?"

The answer was more revealing than expected.

| Property | Details |
|----------|---------|
| Tool | Microsoft Excel |
| Dataset | 100,000 Amazon transactions |
| Time Period | 2020 — 2024 |
| Countries | USA, India, Canada, UK, Australia |
| Deliverables | Dashboard, Insights & Recommendations |



## 🚨 Business Problem

Amazon processes millions of transactions globally but volume 
alone does not guarantee business health. With 100,000 orders 
across 5 countries and 5 years, critical warning signals can 
easily get buried in the noise of "stable" revenue figures.

This analysis was built to investigate the questions that 
standard sales reports rarely ask:

- Why are all 4 key business metrics declining simultaneously 
  in 2024?
- Where is revenue being lost silently through cancellations 
  and returns?
- Are the markets outside the US being developed or neglected?
- Is Amazon's discount strategy actually working or quietly 
  destroying margins?
- Which products, brands and payment methods are truly driving 
  the business forward?

The data had answers to all of these. Most of them were 
uncomfortable.



## 📁 Dataset

| Property | Details |
|----------|---------|
| Source | Kaggle |
| Records | 100,000 transactions |
| Time Period | 2020 — 2024 |
| Countries | United States, India, Canada, United Kingdom, Australia |

Key Fields:

| Column | Description |
|--------|-------------|
| Order ID | Unique transaction identifier |
| Order Date | Date of purchase |
| Customer ID | Unique customer identifier |
| Customer Name | Name of customer |
| Product ID | Unique product identifier |
| Product Name | Name of product sold |
| Category | Product category |
| Brand | Product brand |
| Quantity | Units purchased |
| Unit Price | Price per unit |
| Discount | Discount applied (stored as decimal — 0.05 = 5%) |
| Tax | Tax applied to order |
| Shipping Cost | Delivery cost |
| Total Amount | Final order value |
| Payment Method | Method of payment used |
| Order Status | Current status of order |
| City | Customer city |
| State | Customer state |
| Country | Customer country |
| Seller ID | Unique seller identifier |



## 🧹 Data Cleaning Process

100,000 rows. 20 columns. Zero shortcuts.

✅ Zero duplicate Order IDs found

✅ Zero blank cells across all 20 columns

✅ All data types validated and corrected

✅ Text consistency verified across all categorical columns

⚠️ Critical Finding: Discount stored as decimal 
   (0.05 = 5%) — not flat currency
   
✅ Helper columns created: Month & Year for pivot analysis



## 🔍 Analysis Approach

The analysis was structured around 4 core KPIs and 
5 critical business questions, each designed to go
beyond surface reporting and into strategic territory.
4 Core KPIs Tracked:

| KPI | Value | YoY Indicator |
|-----|-------|--------------|
| 💰 Total Revenue | $91.8M | ▼ 1.88% vs PY |
| 📦 Total Orders | 100K | ▼ 1.12% vs PY |
| 🛒 Average Order Value | $918.26 | ▼ 0.76% vs PY |
| 📫 Total Units Sold | 300.1K | ▼ 1.63% vs PY |

5 Critical Business Questions:
- Why are all 4 metrics declining simultaneously in 2024?
- Where is revenue leaking through cancellations and returns?
- Are markets outside the US being developed or neglected?
- Is the discount strategy working or destroying margins?
- Which products, brands and payment methods drive the business?

12 Pivot Tables built to power the analysis:

| Pivot Table | Purpose |
|-------------|---------|
| PT1 | Total Revenue by Year |
| PT2 | Total Orders by Year |
| PT3 | Average Order Value by Year |
| PT4 | Total Units Sold by Year |
| PT5 | Monthly Revenue by Year |
| PT6 | Revenue & Discount by Category |
| PT7 | Revenue & Orders by Country |
| PT8 | Orders by Status |
| PT9 | Top 5 Products by Revenue |
| PT10 | Returns & Cancellations by Country |
| PT11 | Revenue by Payment Method |
| PT12 | Revenue by Brand (Top 10) |



## 📊 Dashboard

The final deliverable is a fully interactive Excel 
dashboard built to communicate findings clearly and 
efficiently to both technical and non-technical audiences.


<img width="1876" height="917" alt="Amazon dashboard pics" src="https://github.com/user-attachments/assets/82558eb0-03b6-4056-bf59-92f06c04f573" />






## 🔑 Key Findings

Finding 1 — A Silent but Dangerous Revenue Decline
2024 is the worst performing year across all 4 KPIs 
simultaneously. When all metrics decline together it 
is never seasonal, it is structural. This is an early 
warning signal that demands immediate strategic response.

Finding 2 — $5.6M Hidden Revenue Leakage
6,077 orders were cancelled or returned across 5 years. 
At an average order value of $918.26, this represents 
approximately $5.6M in lost or at-risk revenue quietly 
leaving the business through operational inefficiency.

Finding 3 — 70% Revenue Concentration is a Strategic Risk
The United States generates $64.3M — 70% of total revenue. 
A single market disruption could devastate Amazon's entire 
revenue base overnight.

Finding 4 — Discounts Are Not Driving Revenue
Home & Kitchen carries the highest discount rate (7.51%) 
yet ranks 4th in revenue. Electronics generates the highest 
revenue with a lower discount rate. Demand, not discounting 
drives performance.

Finding 5 — India is a Problem Market in Disguise
India is Amazon's 2nd largest market yet carries 900 
problematic orders, the highest proportional rate outside 
the US. A market this important cannot afford operational 
inefficiency at this scale.

Finding 6 — Credit Cards Are the Revenue Engine
Credit Card transactions drive 35% of total revenue ($32.1M) 
more than double the next payment method. Amazon's highest 
value customers are digital, card-driven and ready to be 
rewarded.



## 💡 Insights

*9 business insights uncovered from this analysis. 
Key highlights below , full insights available in 
the Excel Dashboard.*

1. 2024 is declining across every metric; structural, 
   not seasonal.
2. Discounts are not driving sales, demand is.
3. The US holds 70% of revenue ; four markets are 
   being ignored.
4. $5.6M in revenue quietly walking out the door.

📂 View full insights in the Excel Dashboard



## 🎯 Recommendations

*9 strategic recommendations derived from this analysis. 
Key highlights below , full recommendations available 
in the Excel Dashboard.*

1. Reverse the 2024 decline now , before it becomes 
   a crisis in 2025.
2. Stop discounting Home & Kitchen , redirect budget 
   to Electronics.
3. 70% revenue from one market is not growth , it is 
   risk. Diversify urgently.
4. $5.6M in lost orders demands a returns reduction 
   programme immediately.

📂 View full recommendations in the Excel Dashboard



## Tools Used

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Data Cleaning, Analysis & Dashboard |
| Pivot Tables | 12 pivot tables powering all KPIs and charts |
| Excel Formulas | GETPIVOTDATA, IFERROR, TEXT, YEAR, COUNTIF |
| Data Visualization | Line, Bar, Donut Charts |
| Conditional Formatting | Duplicate detection & data validation |
| Custom Number Formatting | Professional KPI display ($91.8M, 100K, 300.1K) |



## About the Analyst

Odu Deborah — Data Analyst

I don't just analyze data, I find the story the numbers 
are trying to tell and translate it into decisions 
businesses can act on.

This project is a demonstration of that approach, 
starting from 100,000 raw transactions and ending with 
9 actionable recommendations that could directly impact 
Amazon's revenue strategy.

🔗 [Connect with me on LinkedIn]https://www.linkedin.com/in/odu-deborah

📧 Email: debbytosin400@gmail.com

💼 Available for data analyst roles and freelance projects



*"The goal of data analysis is not to describe what 
happened, it is to change what happens next."*

---

⭐️ If this analysis gave you value, please star this repository!

