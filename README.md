# 📊 Sales Forecasting & Revenue Trend Analysis

> **End-to-end Business Analyst Portfolio Project** — Revenue analytics, sales forecasting, KPI dashboards, and strategic recommendations using Microsoft Excel

![Project Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![Tool](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346)
![Data](https://img.shields.io/badge/Transactions-120-blue)
![Period](https://img.shields.io/badge/Period-Jan%202023%20–%20Dec%202024-navy)

---

## 📌 Project Overview

This project simulates the work of a Sales Analyst or Business Analyst at a mid-size organisation. Starting from raw transactional data, I performed end-to-end analysis to uncover revenue trends, measure forecast accuracy, identify regional and product performance gaps, and deliver a structured set of business recommendations — all presented through a professional Excel dashboard and a formal recommendations report.

---

## 🎯 Business Problem

The sales and finance teams needed answers to four core questions:

1. Are we hitting our revenue targets — and if not, where are we falling short?
2. How accurate are our sales forecasts, and which segments are hardest to predict?
3. Which regions and products are driving growth, and which are underperforming?
4. What actions should leadership take in Q1 2025 to improve performance?

---

## 📁 Repository Structure

```
sales-forecasting-revenue-trend-analysis/
│
├── README.md
│
├── dataset/
│   └── Sales_Forecasting_Dataset.xlsx        ← Raw dataset + 6 analysis sheets
│
├── dashboard/
│   └── Sales_Forecasting_Dashboard.xlsx      ← Interactive Excel dashboard (8 charts)
│
├── reports/
│   └── Sales_Forecasting_Recommendations_Report.docx  ← Full business report
│
├── docs/
│   └── Sales_Forecasting_Project_Documentation.docx   ← Step-by-step project guide
│
└── screenshots/
    └── (add dashboard screenshots here)
```

---

## 🗂️ Dataset Description

| Property | Details |
|---|---|
| **Rows** | 120 sales transactions |
| **Columns** | 23 fields per transaction |
| **Time Period** | January 2023 – December 2024 (24 months) |
| **Regions** | North, South, East, West, Central |
| **Product Categories** | Software, Hardware, Services, Consulting, Subscriptions |
| **Customer Segments** | Enterprise, Mid-Market, SMB, Government |
| **Sales Reps** | 10 named representatives |

### Column Reference

| Column | Type | Description |
|---|---|---|
| Order ID | Text | Unique transaction identifier |
| Order Date | Date | Date of the order (YYYY-MM-DD) |
| Month / Quarter / Year | Number/Text | Time dimension fields |
| Region / Country | Text | Geographic fields |
| Customer Segment | Text | Enterprise, Mid-Market, SMB, Government |
| Product Category / Name | Text | Product dimension fields |
| Sales Representative | Text | Rep who closed the deal |
| Units Sold | Number | Quantity sold |
| Unit Price (₹) | Currency | Price per unit |
| Revenue (₹) | Currency | Units × Unit Price |
| Cost (₹) | Currency | Total cost of the order |
| Profit (₹) | Currency | Revenue − Cost |
| Marketing Spend (₹) | Currency | Allocated marketing investment |
| Forecasted Revenue (₹) | Currency | Pre-order revenue prediction |
| Actual Revenue (₹) | Currency | Confirmed revenue |
| Revenue Variance % | Percentage | ((Actual − Forecast) / Forecast) × 100 |
| Sales Target (₹) | Currency | Revenue target for the period |
| Target Achievement % | Percentage | (Actual / Target) × 100 |
| Season | Text | Winter / Spring / Summer / Autumn |

---

## 📊 Excel Workbook — Sheet Guide

### Dataset File (`Sales_Forecasting_Dataset.xlsx`)

| Sheet | Contents |
|---|---|
| **Sales Data** | Full 120-row dataset, all 23 columns, auto-filter enabled |
| **KPI Summary** | 10 KPIs with live SUMIF/AVERAGEIF formulas |
| **Regional Analysis** | Revenue, Profit, Margin, Target Achievement by Region |
| **Product Analysis** | Revenue, Units, Avg Price, Profit by Product Category |
| **Forecast vs Actual** | Variance analysis for 30 orders + summary statistics |
| **Monthly Trend** | 24-month revenue and profit trend table |

### Dashboard File (`Sales_Forecasting_Dashboard.xlsx`)

| Chart / Element | Type | Data Source |
|---|---|---|
| 5 KPI Cards | Formatted cells | Calculated from dataset |
| Monthly Revenue & Profit | Clustered bar (24 months) | Monthly Trend sheet |
| Forecast vs Actual | Grouped bar (20 orders) | ChartData sheet |
| Revenue by Region | Horizontal bar | ChartData sheet |
| Product Category Analysis | Horizontal bar (Revenue + Profit) | ChartData sheet |
| Customer Segment Split | Pie chart with % labels | ChartData sheet |
| Quarterly Revenue | Column chart with data labels | ChartData sheet |
| Revenue Variance % | Column chart (30 orders) | ChartData sheet |
| Profitability by Product | Grouped bar | ChartData sheet |
| Region Target Table | Formatted mini-table | Inline |
| Insight Boxes | Colour-coded text panels | Inline |

---

## 📈 Key Results

### KPI Summary

| KPI | Value | Benchmark | Status |
|---|---|---|---|
| Total Revenue | ₹9,282,162 | Growing YoY | ✅ On Track |
| Profit Margin % | 44.18% | > 30% | ✅ Healthy |
| Forecast Accuracy % | 99.57% | > 85% | ✅ Excellent |
| Target Achievement % | 93.56% | > 95% | ⚠️ Below Target |
| Avg Revenue per Order | ₹77,351 | Trend Upward | ✅ Stable |
| Marketing ROI | 9.6× | > 5× | ✅ Strong |

### Regional Performance

| Region | Revenue | Share | Target Achievement |
|---|---|---|---|
| South | ₹2,868,169 | 30.9% | 92.31% ⚠️ |
| East | ₹1,908,239 | 20.6% | 93.99% |
| North | ₹1,652,868 | 17.8% | 96.88% ✅ |
| West | ₹1,610,590 | 17.3% | 92.08% ⚠️ |
| Central | ₹1,242,295 | 13.4% | 93.54% |

### Product Profitability

| Category | Revenue | Profit Margin |
|---|---|---|
| Software | ₹2,859,100 | 45.7% |
| Consulting | ₹1,956,583 | 42.1% ⭐ Highest Margin |
| Subscriptions | ₹1,822,995 | 44.8% |
| Hardware | ₹1,480,794 | 42.8% |
| Services | ₹1,162,690 | 45.0% |

---

## 💡 Key Insights

**1. Q4 Seasonality is Extreme**
Q4 (Oct–Dec) delivers ₹3.15M — 33.9% of annual revenue. Monthly targets do not reflect this, causing reactive resource strain every Q4.

**2. South Region Over-Concentration**
South generates 30.9% of total revenue. While strong, this geographic concentration creates risk. Central (13.4%) is significantly underutilised.

**3. Consulting is the Hidden Gem**
Consulting has the highest profit margin in the portfolio (42.1%) yet is the second-lowest revenue contributor. Shifting the product mix toward Consulting would improve overall profitability without proportional cost increases.

**4. SMB Segment Drags Target Achievement**
The SMB segment records the most frequent target misses. Targets appear calibrated to Enterprise deal sizes, not SMB deal cycles.

**5. Subscription Revenue is the Most Predictable**
Subscription orders show near-zero forecast variance — ideal for financial planning. Services and Consulting show the widest variance due to milestone-based revenue recognition.

---

## 🛠️ Tools & Techniques

| Category | Details |
|---|---|
| **Primary Tool** | Microsoft Excel |
| **Key Functions** | `SUMIF`, `AVERAGEIF`, `FORECAST.LINEAR`, `IFERROR`, `IF`, `SUM`, `AVERAGE` |
| **Excel Features** | Pivot Tables, Slicers, Conditional Formatting, Combo Charts, Data Validation |
| **Analysis Types** | Revenue Trend, Forecasting, Variance Analysis, Profitability, Regional, Seasonal |
| **Deliverables** | Dataset, Dashboard, Recommendations Report, Project Documentation |

---

## 📋 Recommendations Summary

| # | Priority | Recommendation | Expected Benefit | Timeline |
|---|---|---|---|---|
| 1 | 🔴 HIGH | Redesign SMB target model with segment-specific benchmarks | Achievement +5–8% | Q1 2025 |
| 2 | 🔴 HIGH | Launch Central & West growth campaign with 20% incremental budget | Regional revenue +15–20% | Q1 2025 |
| 3 | 🔴 HIGH | Implement seasonal target-setting to reflect Q3–Q4 demand surge | Capacity planning +25% | Q1 2025 |
| 4 | 🟡 MEDIUM | Train Sales on Consulting upsell; create Software + Consulting bundles | Margin +3–5 pts | Q2 2025 |
| 5 | 🟡 MEDIUM | Integrate CRM pipeline data into forecast model for project categories | Forecast accuracy +8% | Q2 2025 |
| 6 | 🟡 MEDIUM | Launch SMB 90-day onboarding retention programme | Churn −15% | Q2 2025 |
| 7 | 🟢 LOW | Review Hardware pricing; evaluate EOL for low-margin SKUs | Margin +4–6 pts | Q3 2025 |
| 8 | 🟢 LOW | Deploy real-time target-achievement BI dashboard with weekly digest | Reporting visibility +100% | Q3 2025 |

---

## 🗺️ Implementation Roadmap

```
Q1 2025 — Phase 1: Quick Wins
├── Redesign SMB target model
├── Launch Central & West growth campaign
└── Implement seasonal target-setting

Q2 2025 — Phase 2: Capability Build
├── Consulting upsell programme & bundled offers
├── CRM pipeline integration for forecasting
└── SMB 90-day retention onboarding

Q3 2025 — Phase 3: Automation & Tooling
├── Real-time target-achievement BI dashboard
├── Automated weekly sales digest
└── Hardware pricing & SKU rationalisation

2026 Ongoing — Phase 4: Continuous Improvement
├── Monthly KPI review cadence
├── Predictive analytics for Q4 surge planning
└── Annual target-setting governance framework
```

---

## 🚀 How to Use This Project

1. **Download** `Sales_Forecasting_Dataset.xlsx` from the `/dataset/` folder
2. **Open** `Sales_Forecasting_Dashboard.xlsx` from the `/dashboard/` folder
3. **Explore** the 8 charts and 5 KPI cards on the Dashboard tab
4. **Filter** using the Region Target Achievement mini-table to drill into specific regions
5. **Read** the `Sales_Forecasting_Recommendations_Report.docx` for full findings and strategy
6. **Follow** the step-by-step guide in `Sales_Forecasting_Project_Documentation.docx` to replicate the analysis

---

## 📚 What I Learned

- How to structure a complete end-to-end BA project from problem statement to recommendation
- Applying `FORECAST.LINEAR` for real-world revenue extrapolation
- How to build a professional Excel dashboard that communicates to non-technical stakeholders
- The difference between high-revenue and high-profit segments — and why it matters strategically
- How to frame data insights as actionable business recommendations using the SMART framework

---

## 🤝 Connect

**Prepared by:** Debarati
**Date:** June 2026
**LinkedIn:** [your-linkedin-url]

---

*This project is created for portfolio and educational purposes.*
