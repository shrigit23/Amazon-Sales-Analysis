# Amazon Sales & Revenue Analysis — Power BI Dashboard

## Overview
This project delivers an end-to-end **Sales & Revenue Analysis Dashboard** built in Power BI, analyzing **89,083 Amazon transaction records** to help stakeholders track performance, identify top-performing products, and understand customer sentiment through review data. The dashboard combines time-based trend analysis, product-level performance ranking, and category-wide comparisons into a single interactive view.

## Business Problem
Retail and e-commerce teams need a consolidated view of sales performance to make fast, informed decisions — but raw transactional data alone doesn't answer questions like *"Which products are driving revenue?"* or *"Are we trending up or down this quarter?"* This dashboard was built to close that gap by turning 89K+ raw sales records into decision-ready insights.

## KPIs Tracked
| KPI | Purpose |
|---|---|
| **YTD Sales** | Monitors year-to-date revenue performance over time |
| **QTD Sales** | Tracks quarterly sales to surface trends and fluctuations |
| **YTD Products Sold** | Measures total product volume moved during the year |
| **YTD Reviews** | Tracks year-to-date customer review volume as a proxy for satisfaction and engagement |

## Dataset
**`Amazon_Combined_Data.xlsx`** — 89,083 records across 6 fields:

| Column | Description |
|---|---|
| Product Category | Category classification of the product |
| Product Description | Product name/description |
| Price (Dollar) | Unit sale price |
| Number of Reviews | Total customer reviews received |
| Shipment | Shipment/fulfillment status |
| Order Date | Date the order was placed |

## Key Insights Enabled
- **Revenue trend visibility** — month-over-month and week-over-week sales patterns to detect seasonality
- **Product prioritization** — identifies the top 5 revenue-generating and best-reviewed products for inventory and marketing focus
- **Category performance** — heat-map view of which categories over- or under-perform
- **Time-flexible analysis** — YTD and QTD KPIs let stakeholders assess both long-term and short-term performance at a glance

## Files in this Repository
- `amazon_sales_analysis.pbix` — Interactive Power BI report
- `Amazon_Combined_Data.xlsx` — Source dataset (89,083 records)

## Tools & Techniques
Power BI · DAX · Data Modeling · KPI Card Visuals · Trend Analysis · Category Heat Mapping · Interactive Slicers
