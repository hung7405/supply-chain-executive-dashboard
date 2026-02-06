# 📊 Supply Chain Executive Performance Dashboard
**Business & Operations Analytics | Power BI – SQL – Excel**

## 📌 Project Overview
This project delivers an executive-level Supply Chain dashboard designed to support business and operations decision-making. It provides a holistic view of sales performance, profitability, order fulfillment efficiency, and delivery operations, enabling stakeholders to quickly identify growth drivers, operational risks, and improvement opportunities.

The project simulates a real-world reporting scenario where data analysts support management with weekly/monthly executive reports and operational insights.

## 🎯 Business Objectives
* **Monitor Performance:** Track Net Sales, Profit Margin, Order Fulfillment (OTIF), and Delivery Performance.
* **Identify Growth:** Spot key markets and customer segments with high potential.
* **Operational Audit:** Detect inefficiencies causing late deliveries and cancellations.
* **Strategic Support:** Provide data-driven recommendations for inventory, shipping, and cost optimization.

## 📈 Key Metrics & KPIs
### 💰 Business Performance
* **Net Sales & Order Profit Margin (%)**
* **Total Demand vs. Orders Fulfilled**
* **Lost Revenue:** Impact of cancelled orders.

### 🚚 Supply Chain & Operations
* **OTIF (On-Time In-Full) %**
* **Late Delivery & Cancellation Rates**
* **Average Days Delayed / Early**
* **Delivery Status Breakdown:** On-Time, Late, Advanced, Cancelled.

## 🔍 Key Insights
* **Market Drivers:** Europe & LATAM are the primary growth markets, contributing **50%+** of total revenue.
* **Segment Dominance:** The **Consumer** segment dominates sales volume across all markets.
* **Profitability Gap:** The *Fishing* category leads in sales but shows low profit margins, indicating a need for cost optimization.
* **Shipping Bottlenecks:** OTIF performance is low (**43.02%**), primarily driven by **Standard Class** shipping (accounting for 54.8% of late deliveries).
* **Geographic Risks:** High concentration of late orders observed in **Ann Arbor and Atlanta**.

## 🧠 Executive Recommendations
* **Business Strategy:**
    * Prioritize Europe & LATAM with targeted pricing and inventory strategies.
    * Review cost structures for high-volume, low-margin categories like *Fishing*.
* **Operational Improvements:**
    * Re-evaluate **Standard Class** shipping SLAs and service levels.
    * Implement **OTIF monitoring** as a core operational KPI.
    * Proactive intervention for overdue orders in high-risk cities.

## 🛠️ Tools & Technologies
* **Power BI:** DAX, Power Query, Data Modeling (Star Schema), Interactive Dashboards.
* **SQL:** Data extraction, complex joins, and KPI logic calculations.
* **Excel:** Data validation, pivot tables, and initial preprocessing.

## 📷 Dashboard Preview
- [![Supply Chain Executive Dashboard Page Business](Dashboard%20picture/Business%20Health%20Page)](https://app.powerbi.com/groups/me/reports/0f2e5f7d-03a5-469d-85ef-36d6c6bcc9a2/c665dd7a2505cc984179?experience=power-bi)


- [![Supply Chain Executive Dashboard Page Operation](Dashboard%20picture/Operation_Supply%20Chain%20Page)](https://app.powerbi.com/groups/me/reports/0f2e5f7d-03a5-469d-85ef-36d6c6bcc9a2/3551e71d7723dc101c74?experience=power-bi)


## 📂 Repository Structure
```text
Supply-Chain-Executive-Dashboard/
│
├── data/
│   ├── raw/                # Raw transactional data
│   └── processed/          # Cleaned & transformed datasets
│
├── dashboard/
│   └── Supply_Chain_Dashboard.pbix
│
├── screenshots/            # Dashboard visuals
│   ├── business_overview.png
│   └── operations_overview.png
│
└── README.md


