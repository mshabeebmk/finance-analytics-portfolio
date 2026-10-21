# Project 01 — Financial Performance Dashboard (Excel)

**Portfolio project:** Excel management reporting, P&L and budget variance analysis  
**Company:** Northstar Business Services (**fictional**)  
**Reporting period:** January–December 2025  
**Currency:** Indian Rupees (₹)  
**Data:** Fully synthetic for demonstration. No employer or client financial data is used.

## Business question

How can a finance team convert monthly account-level actuals and budgets into an executive view of operating performance, profitability and variances?

## Deliverables

- [Download the Excel workbook](Financial_Performance_Dashboard_Fictional_FY2025.xlsx)
- [Dashboard preview](Financial_Dashboard_Preview.png)

## Workbook structure

| Sheet | Contents |
|---|---|
| Executive Dashboard | Annual KPI cards, actual vs budget monthly scorecard and charts |
| Monthly P&L | Formula-driven monthly revenue, COGS, operating expenses, EBITDA and variances |
| Actual Data | 120 synthetic input records across 10 revenue and cost categories |
| Budget Data | Matching illustrative monthly budget assumptions |
| Category Analysis | Year-to-date actual-vs-budget analysis by category and favorability |
| Read Me | Definitions, methodology and synthetic-data disclaimer |

## Key findings (illustrative)

- **Revenue:** ₹17,396,500 (approximately ₹1.74 crore).
- **EBITDA:** ₹6,349,800 and **EBITDA margin:** 36.5%.
- **EBITDA vs budget:** ₹243,900 favorable for the full year.
- **Largest monthly favorable EBITDA variance:** 2025-09 (₹155,100).
- **Largest monthly unfavorable EBITDA variance:** 2025-05 (₹-112,000).

## Method

1. Group monthly actual and budget records into revenue, cost of goods sold (COGS), and operating expenses.
2. Use Excel `SUMIFS` formulas to build a linked monthly P&L.
3. Calculate gross profit (`Revenue − COGS`) and operating EBITDA (`Gross Profit − Operating Expenses`).
4. Compare actual performance against plan and highlight favorable/unfavorable differences.
5. Present a concise dashboard and monthly trends with native Excel charts.

## Portfolio discussion points

- Explain **why an unfavorable profit variance** matters more than revenue growth alone.
- Drill into category-level actual/budget differences and discuss possible operating drivers.
- Explain how you would perform root-cause analysis, working-capital review or rolling forecasts using real (authorized) data.

## Ethical disclosure

This project is a **practice case study created using fictional data**, not a record of actual work for any employer. Figures are illustrative and unaudited. Verify and understand the workbook's calculations before discussing it in an interview.
