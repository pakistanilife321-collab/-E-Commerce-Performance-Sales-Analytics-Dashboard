# 📊 E-Commerce Performance & Sales Analytics Dashboard decodelab project 4


## 📌 Business Overview
This interactive Power BI Executive Dashboard provides key stakeholders with real-time visibility into sales revenue, customer retention, fulfillment performance, and marketing channel ROI. By connecting multi-channel data sources into a centralized BI model, this dashboard enables business leaders to monitor quarterly benchmarks, track payment method distributions, and analyze regional sales concentration.

---

## 🛠️ Key Metrics & Features (KPIs)
- **Sum of Total Revenue:** $1.26M overall revenue tracking across fiscal quarters.
- **Sum of Total Orders:** 1.00K total completed orders.
- **Sum of Total Units Sold:** 3.54K items fulfilled.
- **Quarterly Slicers:** Interactive Q1–Q4 filtering for granular temporal trend analysis.
- **Geographic Mapping:** Interactive map visualization identifying top revenue-generating delivery locations across the US.
- **Order Status Breakdown:** Real-time fulfillment tracking (*Delivered, Pending, Cancelled, Returned*).

---

## 📊 Dashboard Visualizations & Structure

| Visual Component | Chart Type | Key Business Metric / Insight |
| :--- | :--- | :--- |
| **KPI Top Cards** | Scorecard / Multi-Card | High-level overview of Revenue ($1.26M), Orders (1K), and Units Sold (3.54K). |
| **Quarter Slicers** | Button Slicers | Enables seamless single and multi-quarter comparison filtering. |
| **Customer LTV Table** | Matrix / Table | Breakdown of Customer ID, Quantity, and Total Spend ($1.26M+ overall). |
| **Revenue by Channel** | Horizontal Bar Chart | Performance breakdown across Instagram, Email, Google, Product, Search, & Referral. |
| **Payment Method Share** | Donut Chart | Proportion of sales via Online, Cash, Credit Card, Debit Card, & Gift Cards. |
| **Fulfillment Status** | Pie Chart | Evaluates order cycle efficiency (*21% Cancelled, 21% Returned, 20% Pending, 19% Delivered*). |
| **Geographic Density** | Bubble Map | Heatmap of order volume and total revenue by shipping address. |

---

## 📐 Data Modeling & DAX Measures
- **Data Transformation:** Performed ETL operations in Power Query (data type validation, null removal, and custom columns).
- **Relational Modeling:** Built a star schema establishing one-to-many relationships between facts (`orders`, `order_items`) and dimensions (`customers`, `date_table`).
- **Custom DAX Measures:** Developed calculated measures for dynamic revenue aggregation, monthly tracking, and quarterly comparisons.

---
