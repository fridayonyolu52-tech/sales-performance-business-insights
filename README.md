# Project 03 — Sales Performance & Business Insights

## Project Overview

This project demonstrates an end-to-end sales analysis workflow in Microsoft Excel, from raw transactional data through validation, KPI development, business analysis, and dashboard reporting.

The workbook contains **500 sales transactions covering January–December 2025**.

## Objective

The analysis was designed to:

- Validate the quality and consistency of the sales dataset.
- Calculate core sales and profitability KPIs.
- Analyze performance by product, category, region, salesperson, and month.
- Reconcile summary calculations against the underlying transaction data.
- Present the results in an executive-style Excel dashboard.

## Tools & Techniques

- Microsoft Excel
- Excel formulas
- Data validation and quality checks
- Summary analysis
- Pivot-style analysis
- KPI development
- Line and column charts
- Dashboard design

## Key Metrics

| Metric | Result |
|---|---:|
| Total Revenue | 680,363.20 |
| Total Cost | 429,297.00 |
| Total Profit | 251,066.20 |
| Units Sold | 2,710 |
| Number of Orders | 500 |
| Average Order Value | 1,360.73 |
| Overall Profit Margin | 36.90% |

## Analysis Included

### Product Analysis
Revenue, profit, and profit margin are analyzed across the product range.

### Category Analysis
Revenue, profit, quantity, and profit margin are summarized by category.

### Regional Analysis
Revenue, profit, quantity, and profit margin are compared across East, North, South, and West.

### Salesperson Analysis
Sales performance is summarized across the six salespeople represented in the dataset.

### Monthly Analysis
Monthly revenue, profit, quantity, and profit margin are analyzed across 2025.

## Data Quality & Validation

The workbook includes a dedicated **Data Inspection** sheet covering:

- Record count
- Column count
- Date range
- Quantity validation
- Unit-price validation
- Discount validation
- Revenue validation
- Cost validation
- Profit reconciliation
- Profit-margin reconciliation

The final audit confirmed:

- 500 transaction records
- 500 unique order IDs
- No revenue calculation mismatches
- No profit calculation mismatches
- No profit-margin calculation mismatches
- All quantities are positive
- All unit prices are positive
- Discount values fall within the documented 0–15% range

## Dashboard

The `Dashboard` worksheet provides:

- Total Revenue KPI
- Total Profit KPI
- Units Sold KPI
- Profit Margin KPI
- Monthly Revenue Trend
- Revenue by Category
- Revenue by Region

The dashboard KPI cells are linked to the `Sales Analysis` worksheet so that the displayed KPI values remain connected to the underlying analysis.

## Workbook Structure

```text
Project_03_Sales_Performance_Business_Insights/
│
├── sales_performance_analysis_final.xlsx
└── README.md
```

## How to Use

1. Download or open `sales_performance_analysis_final.xlsx`.
2. Start with the `Dashboard` sheet for the executive summary.
3. Review `Sales Analysis` for the core KPIs.
4. Explore the product, category, regional, salesperson, and monthly analysis sheets.
5. Review `Data Inspection` for the validation checks.
6. Use `Raw_Sales_Data` to inspect the underlying transactions.

## Portfolio Skills Demonstrated

- Data cleaning and validation
- Excel data analysis
- KPI development
- Financial and profitability calculations
- Business performance analysis
- Data quality documentation
- Dashboard development
- Data visualization
- Analytical reconciliation
- Professional workbook organization
