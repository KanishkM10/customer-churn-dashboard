# 📉 Customer Churn Dashboard — Power BI

> A multi-page customer churn analytics dashboard built in **Microsoft Power BI**, developed as part of the **DataCamp Data Analyst Associate certification** track. The dashboard dissects churn behaviour across demographics, contract types, usage patterns, and geography to help telecom businesses identify and act on retention risks.

---

## 🗂️ Project Overview

Customer churn is one of the most critical KPIs for subscription-based businesses. This dashboard provides a structured, 10-page analytical deep-dive into churn drivers — enabling decision-makers to identify at-risk segments, understand root causes, and compare churn patterns across product and contractual dimensions.

---

## 📄 Dashboard Pages

### 1. 🏠 Overview
A high-level executive summary of churn health.
- **KPI Cards** — Overall Churn Rate, total customer count, key aggregate metrics
- **Churn Reasons** — Clustered bar chart ranking reasons customers leave
- **Churn by Category** — Pie chart grouping churn into broad cause categories
- **Customers by Contract Type** — Donut chart
- **Geographic Churn Map** — State-level churn rate map

---

### 2. 👤 Churn Demographics
Age- and segment-based churn breakdown.
- **Churn Rate by Age Band** — Combo chart (Number of Customers + Churn Rate by age bins)
- **Senior / Under 30 Segment Table** — Tabular churn rate comparison
- **Churn Rate KPI Card**
- **Churn Reasons** — Bar chart filtered to demographic context

---

### 3. 🗃️ Groups and Categories
Churn analysis across customer groupings and contract tiers.
- **Churn Rate by Group Size** — Line + stacked column combo chart
- **Churn by Category** — Pie chart (Competitor, Dissatisfaction, Price, etc.)
- **Churn Rate by Contract Category & Gender** — Clustered column chart
- **Multi-Row Card** — Churn rate per contract category
- **Customers by Contract Type** — Donut chart

---

### 4. 📶 Unlimited Plan
Usage vs. churn interaction for customers on unlimited data plans.
- **Unlimited Plan Summary Table** — Churn rate, plan status, customer count
- **Churn Rate by Data Consumption Group** — Bar chart split by unlimited plan status

---

### 5. 🌍 International Calls
International calling plan adoption and its relationship to churn.
- **Pivot Table** — Churn rate by international plan status and activation status
- **State-Level Map** — Geographic distribution of churn rate

---

### 6. 📄 Contract Type
How contract structure and payment method drive churn.
- **Churn Rate by Account Length** — Line charts showing tenure-churn relationship
- **Churn Rate by Account Length & Contract Type** — Segmented line chart
- **Payment Method Breakdown** — Pie chart (customer count + churn rate)

---

### 7. 👴 Age Groups
Deep-dive into age-driven churn patterns with interactivity.
- **Churn Rate by Age Band** — Combo chart (customers + churn rate)
- **Churn Rate by Customer Group** — Combo chart (group size + churn rate)
- **Account Length Slicer** — Filter visuals by tenure range

---

### 8. 💳 Payment and Contract
Payment behaviour, service interactions, and churn correlation.
- **Avg Customer Service Calls KPI Card**
- **Scatter Chart** — Churn rate by payment method and contract category
- **Slicer** — Filter by contract category and payment method

---

### 9. 💰 Extra Charges
Churn sensitivity to overage and international charges.
- **Avg Extra International Charges KPI Card**
- **Avg Extra Data Charges KPI Card**
- **Churn Rate by Data Consumption** — Bar chart segmented by unlimited plan

---

### 10. 💡 Insights
Summary insights page aggregating key churn signals in one view.
- **KPI Cards** — Churn Rate, Avg Customer Service Calls, Avg Extra International Charges, Avg Extra Data Charges
- **Avg Customer Service Calls by State** — Line chart with churn label overlay
- **State-Level Churn Map** — Geographic summary

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Microsoft Power BI Desktop | Dashboard development & data modeling |
| Power Query (M Language) | Data transformation and cleaning |
| DAX (Data Analysis Expressions) | Churn rate measures, KPIs, segmentation |
| Power BI Map Visual | Geographic churn distribution |
| DataCamp | Project guided learning context |

---

## 📊 Key Metrics Tracked

| Metric | Description |
|--------|-------------|
| **Churn Rate** | % of customers who churned overall and by segment |
| **Churn Reasons** | Ranked reasons why customers left |
| **Churn Category** | High-level grouping (Competitor, Price, Service, etc.) |
| **Avg Customer Service Calls** | Proxy for dissatisfaction |
| **Avg Extra Data Charges** | Overage cost burden |
| **Avg Extra International Charges** | International plan overage |
| **Account Length** | Tenure-based churn risk |
| **Contract Type** | Month-to-month vs. annual churn comparison |

---

## 📁 File Structure

```
customer-churn-dashboard/
│
├── Customer_Churn_Dashboard.pbix   # Main Power BI report file
└── README.md                       # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free) — version **2022.09** or later recommended

### Steps to Open
1. Clone or download this repository
2. Open **Power BI Desktop**
3. Go to **File → Open report → Browse**
4. Select `Customer_Churn_Dashboard.pbix`
5. All 10 pages will load with the embedded data model — no external database required

> ⚠️ **Note:** This report uses an embedded data model. All data is contained within the `.pbix` file and no external connection setup is needed.

---

## 🎓 Certification Context

This project was built as part of the **[DataCamp Data Analyst Associate](https://www.datacamp.com/certification/data-analyst)** certification program. It demonstrates proficiency in:
- Multi-page interactive report design in Power BI
- Customer analytics and churn modelling concepts
- DAX measure creation (rates, averages, segmented KPIs)
- Geographic and demographic data visualization

---

## 👤 Author

**Kanishk**
PGDM — Finance & Business Analytics | MILE Education (Batch 2025–27)
Former Associate Data Engineer @ Celebal Technologies

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-black?style=flat&logo=github)](https://github.com/)

---

## 📜 License

This project is shared for **educational and portfolio purposes**. The dataset used is part of the DataCamp certification coursework.
