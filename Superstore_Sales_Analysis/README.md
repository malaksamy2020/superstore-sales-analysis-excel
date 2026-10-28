# Superstore Sales Analysis — Excel Portfolio Project

## Overview
An interactive Excel sales and profitability analysis project built using the Sample Superstore dataset. The workbook is designed to help explore sales, profit, and product performance through an interactive dashboard and supporting PivotTables.

## Project Highlights
- Interactive Excel dashboard with KPI cards, charts, and slicers for Region and Category
- PivotTable analysis of sales and profit by region, category, and sub-category
- Supporting KPI analysis for revenue, units sold, total profit, and profit margin
- Data-cleaning documentation, including a cleaning log
- Excel Table (`tblSales`) with helper columns for Profit Margin and Net Unit Price

## Key Figures in This Workbook
- **Total Sales:** 2,296,194.59
- **Total Profit:** 286,238.45
- **Units Sold:** 37,820
- **Profit Margin:** approximately 12.47%

*Figures reflect the current workbook and its cleaning choices.*

## Workbook Structure
- `Dashboard` — main dashboard; start here
- `Pivot_Analysis` — sales and profit summaries by region, category, and sub-category
- `overallperf` — supporting KPI PivotTable
- `Data` — cleaned dataset and helper columns
- `Cleaning Log` — documents cleaning decisions and removed rows
- `README` — in-workbook project notes

## Data Cleaning Notes
The workbook documentation reports 9,994 source rows and 9,977 rows after removing 17 exact duplicate rows. Postal codes are preserved as text and leading-zero issues were corrected. The cleaning log records the removed rows for auditability.

## How to Use
1. Download `Superstore_Sales_Analysis_Final.xlsx`.
2. Open it in Microsoft Excel (desktop Excel is recommended for interactive slicers and PivotTables).
3. Go to the `Dashboard` sheet.
4. Use the Region and Category slicers to explore the dashboard.
5. Review `Pivot_Analysis` and `Cleaning Log` for supporting analysis and documentation.

## Tools
- Microsoft Excel
- PivotTables and charts
- Slicers
- Data cleaning and formula-based helper columns

## Notes and Limitations
The source dataset does not include Order Date or Ship Date, so time-series, monthly, and year-over-year analyses are not included. Some Excel interactive features may not work fully in spreadsheet viewers other than Microsoft Excel.

## Acknowledgment
Completed as a project task during my Elevvo internship.
