# Sales Forecasting & Revenue Trend Analysis

> **Business Analyst Portfolio Project** — End-to-end sales forecasting and revenue analysis using Microsoft Excel

---

## Project Overview

An end-to-end Business Analyst project that analyzes 120+ historical sales transactions across 5 regions, 5 product categories, and 4 customer segments to forecast future revenue, track KPIs, identify trends, and deliver actionable business recommendations.

Built with **Microsoft Excel** using `FORECAST.LINEAR`, `SUMIF`, `AVERAGEIF`, Pivot Tables, and interactive slicers.

---

## Business Problem

The sales and finance teams needed a reliable method to:
- Compare forecasted vs actual revenue across regions and products
- Identify which regions and products are missing targets
- Understand seasonal revenue patterns for better planning
- Build a dashboard for monthly and quarterly business reviews

---

## Dataset Description

| Property | Details |
|----------|---------|
| Rows | 120 sales transactions |
| Columns | 23 (Order ID, Date, Region, Product, Revenue, Cost, Profit, Forecast, Target, Season, etc.) |
| Time Period | January 2023 – December 2024 |
| Regions | North, South, East, West, Central |
| Product Categories | Software, Hardware, Services, Consulting, Subscriptions |
| Customer Segments | Enterprise, Mid-Market, SMB, Government |

---

## Analysis Performed

- **Revenue Trend Analysis** — 24-month monthly revenue trend
- **Sales Forecasting** — Using `FORECAST.LINEAR()` to predict Q1 2025
- **Variance Analysis** — Forecasted vs Actual Revenue with Variance %
- **Profitability Analysis** — Profit Margin by Product and Region
- **KPI Dashboard** — 5 core KPIs with conditional formatting
- **Regional Analysis** — Revenue and target achievement by region
- **Seasonal Analysis** — Q3/Q4 seasonal revenue patterns

---

## Excel Workbook Structure

| Sheet | Contents |
|-------|---------|
| `Sales Data` | Full 120-row dataset with all 23 columns |
| `KPI Summary` | 10 KPIs with live formulas |
| `Regional Analysis` | Revenue, Profit, Margin, Target Achievement by Region |
| `Product Analysis` | Revenue, Units, Avg Price, Profit by Product Category |
| `Forecast vs Actual` | Variance analysis for 30 orders + summary stats |
| `Monthly Trend` | 24-month revenue and profit trend table |

---

## Key Insights

1. **North region** generates the highest total revenue — prime candidate for Q1 investment
2. **Subscription category** is most forecastable with lowest variance (~91% accuracy)
3. **Q4** consistently delivers ~35% of annual revenue — set seasonal targets accordingly
4. **SMB segment** misses targets most frequently — targets may be unrealistic or execution needs support
5. **Consulting** shows the highest profit margin despite lower revenue — underutilised opportunity

---

## Recommendations

1. Increase North and East marketing budgets by 20% in Q1 2025 to capitalise on momentum
2. Improve Services and Consulting forecasting by integrating CRM pipeline data
3. Shift product mix toward Subscription and Consulting categories for better margins
4. Set seasonal-adjusted targets for Q4 to better reflect actual demand patterns
5. Launch targeted upsell programs for SMB segment to improve average order value

---

## Tools & Techniques

**Tools:** Microsoft Excel  
**Functions:** FORECAST.LINEAR, SUMIF, AVERAGEIF, IFERROR, IF, SUM, AVERAGE  
**Features:** Pivot Tables, Slicers, Conditional Formatting, Combo Charts  
**Skills:** Business Analysis, Sales Forecasting, KPI Design, Dashboard Development, Variance Analysis

---

## Folder Structure

```
sales-forecasting-revenue-trend-analysis/
│
├── README.md
├── dataset/
│   └── sales_data.xlsx
├── analysis/
│   └── sales_forecast_analysis.xlsx
├── screenshots/
│   └── (add your dashboard screenshots here)
├── reports/
│   └── business_recommendations.docx
└── docs/
    └── project_documentation.docx
```

---

## How to Use

1. Download `sales_data.xlsx` from the `/dataset/` folder
2. Open `sales_forecast_analysis.xlsx` from the `/analysis/` folder
3. Use the **slicers** to filter by Year, Region, Product Category, and Customer Segment
4. Review the `KPI Summary` sheet for high-level performance metrics
5. Read the `business_recommendations.docx` for the full findings and strategic recommendations

---

## Industry Context

- Predictive analytics market growing to **$28 billion by 2032**
- Forecasting improves inventory accuracy by up to **40%**
- Used by companies like Nestle, HUL, Amazon, and Flipkart for monthly business reviews

---

## Project Documentation

Full step-by-step project documentation including dataset description, analysis steps, dashboard design guide, resume descriptions, GitHub upload guide, and LinkedIn showcase content is available in `/docs/project_documentation.docx`.

---

*This project is created for portfolio and educational purposes.*
