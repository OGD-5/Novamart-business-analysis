# NovaMart 2025 — Business Performance & Recovery Analysis

## 📊 Project Overview

NovaMart is a fictional e-commerce business used for this portfolio case study.

This project investigates NovaMart's business performance during 2025 using **MySQL, Tableau, Excel, and business analysis**.

The objective was not simply to create visualizations, but to use data to investigate business questions, identify important performance patterns, and translate the findings into practical areas for management attention.

The project follows a business-focused approach:

**Business Problem → Investigation → Analysis → Findings → Recommendations**

> **Dataset Note:** The dataset used in this project is synthetic/AI-generated and is used for portfolio and learning purposes. It does not represent real NovaMart business data.

---

## 🔎 Business Problem

NovaMart showed signs of weakening performance toward the later part of 2025.

The investigation focused on understanding several areas of the business:

* Revenue performance
* Order volume
* Discount behaviour
* Product profitability
* Product category revenue
* Delivery performance
* Customer ratings

The objective was to identify important patterns in the data and determine which areas required further management investigation.

---

## 🧠 Business Questions

The SQL analysis was structured around the following business questions:

1. **Did revenue decline over the months?**
2. **Did the number of customer orders decrease?**
3. **Were discounts becoming higher toward the later months?**
4. **Which products generated the highest estimated profit?**
5. **Which product categories generated the most revenue?**

An additional calculation was performed to determine the overall average discount.

---

## 🛠️ Tools Used

### MySQL

Used to query the database and investigate the business questions.

SQL techniques used include:

* `SELECT`
* `SUM()`
* `AVG()`
* `COUNT()`
* `GROUP BY`
* `ORDER BY`
* `INNER JOIN`
* Aggregate functions
* Date-based grouping by month

### Tableau

Used to create visualizations and develop the executive dashboard for communicating the findings.

### Excel

Used as part of the supporting data analysis workflow.

### Business Analysis

Used to interpret the analytical findings, identify potential business issues, formulate recommendations, and define areas for further investigation.

---

## 📈 Key Findings

### 1. Revenue Performance

Monthly revenue fluctuated during the first part of the year before a significant decline began around September.

Revenue recovered slightly toward November and December but remained below the stronger performance recorded earlier in the year.

### 2. Order Volume

Order volume followed a similar downward pattern to revenue.

This indicates that the reduction in revenue was accompanied by a reduction in the number of customer orders.

However, this analysis does **not establish the underlying cause** of the decline. Further investigation would be required to determine whether factors such as customer demand, product availability, pricing, seasonality, competition, or other business factors contributed to the change.

### 3. Discount Behaviour

Monthly average discount was analysed to understand how discounting changed throughout the year.

Discounting increased significantly toward the later part of the year.

This creates an important management question:

> **Is increased discounting generating enough additional demand to justify the reduction in margin?**

The analysis identifies the pattern but does **not establish that increased discounting caused the decline in revenue.**

### 4. Product Profitability

Product profitability was estimated using:

**(Selling Price − Cost Price) × Quantity Sold**

This analysis identified which products generated the highest estimated profit based on the available selling-price and cost-price data.

The analysis demonstrates why revenue and profitability should be evaluated separately when making product decisions.

> **Note:** The calculated profit is an estimated product-level profit based on selling price and cost price. It should not be interpreted as net profit because expenses such as tax, salaries, marketing, shipping, and other operating costs were not included in the calculation.

### 5. Revenue by Product Category

Revenue was grouped by product category to identify the categories generating the highest sales revenue.

**Fashion generated the highest category revenue**, followed by Home and Beauty, while Electronics generated the lowest revenue among the categories analysed.

---

## 🚚 Delivery Performance

The project also examined delivery performance through the dashboard.

Out of **560 orders, 96 were delayed**, representing approximately **17.1% of all orders**.

This indicates an area that may require operational investigation.

Further analysis could examine delayed orders by:

* Product
* Location
* Delivery duration
* Time period
* Delivery provider

The current analysis does **not establish that delivery delays caused lower customer ratings**. Instead, the relationship between delivery performance and customer experience should be investigated further.

---

## ⭐ Customer Ratings

Customer ratings were visualized in the Tableau dashboard to provide an overview of customer feedback.

The distribution showed that ratings of **4 and 5 were the largest rating groups**, while ratings of **1–3 also represented a meaningful portion** of the feedback.

This creates an opportunity for further investigation into the factors associated with lower customer ratings.

Potential areas for investigation include:

* Delivery performance
* Product
* Complaint type
* Customer segment
* Order experience

---

## 💡 Business Recommendations

Based on the findings, the following areas were recommended for management attention.

### 1. Diagnose the Revenue and Order Decline

Investigate the underlying factors contributing to the decline in revenue and order volume.

Potential areas include:

* Customer demand
* Customer acquisition and retention
* Product availability
* Pricing
* Seasonality
* Competitive pressure

### 2. Review Discount Effectiveness

Evaluate whether increased discounting is generating sufficient additional sales and orders to justify the reduction in margin.

The relationship between:

**Discount → Orders → Revenue → Profitability**

should be monitored.

### 3. Optimise the Product Portfolio

Evaluate products using:

* Revenue
* Estimated profit
* Profit margin
* Quantity sold

Products can then be classified according to their revenue and profitability performance to support better portfolio decisions.

### 4. Improve Delivery Reliability

Investigate the causes of delayed orders and identify operational bottlenecks.

Reducing delivery delays could improve operational performance and potentially improve customer experience.

### 5. Strengthen Customer Retention

Further customer analysis should examine:

* Purchase frequency
* Recency
* Customer revenue
* Repeat purchases
* Customer retention

This would help identify valuable customers and opportunities to improve repeat purchasing.

### 6. Investigate Lower Customer Ratings

Analyse lower ratings alongside delivery performance, products, complaints, and customer segments to identify potential drivers of poor customer experience.

---

## 📊 Executive Dashboard

The project includes an executive Tableau dashboard designed to bring key performance indicators, trends, and business findings together in one view.

The dashboard focuses on:

* Revenue
* Orders
* Average discount
* Monthly performance trends
* Revenue by category
* Product profitability
* Customer revenue
* Delivery performance
* Customer ratings

The purpose of the dashboard is to help management quickly identify areas requiring attention and further investigation.

## Dashboard Preview

### NovaMart Executive Dashboard

![NovaMart Executive Dashboard](NovaMart-2025-Business-Performance-Analysis/DASHBOARD/NovaMart_Executive_Dashboard.png)

## 📁 Project Structure

```text
NovaMart-business-analysis/
│
├── BUSINESS ANALYSIS/
│   └── NovaMart_2025_Business_Insights_and_Recommendations.pptx
│
├── DASHBOARD/
│   └── Dashboard files and visualizations
│
├── SQL/
│   └── novamart_analysis.sql
│
├── TABLEAU/
│   └── Tableau workbook and related files
│
└── README.md
```

---

## 📌 Project Takeaway

NovaMart reinforced an important principle in business analytics:

> **A dashboard can show you that something changed. The real analytical work begins when you investigate why.**

The project demonstrates how technical tools can be combined with business thinking to move from:

**Data → Insight → Business Action**

---

## 👤 About the Analyst

I'm **Olabode Goodness Daniel (OGD)**, a Mathematics graduate building a career in **Business Analytics**.

I'm particularly interested in using analytical thinking and data to investigate problems around **customer behaviour, revenue, retention, product performance, and business growth**.

This project is part of my portfolio of practical, business-focused analytics projects.
