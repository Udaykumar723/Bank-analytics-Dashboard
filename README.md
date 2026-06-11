# 🏦 Bank Loan Analytics Dashboard
> End-to-end analysis of 66K loan records using SQL, Excel, Power BI & Tableau.

description 
End-to-end bank loan analysis of 66K records (₹751M) using SQL, Excel, Power BI & Tableau — tracking disbursement, recovery, branch performance, and borrower trends across an 8-page interactive dashboard.

Tech stack / tools used

 SQL (SQL Server / MySQL)
- Wrote **13 production-ready queries** covering KPIs, YoY trends, and QTD comparisons
- Used `CASE WHEN` for age bucketing, `UNION ALL` for period comparison
- Applied `WINDOW FUNCTIONS` (`SUM OVER`, `COUNT OVER`) for share calculations
- Aggregated across 6 dimensions: branch, state, year, age, purpose, grade

 Microsoft Excel
- Cleaned 66,000 rows: removed duplicates, handled nulls, standardized dates
- Created derived columns: `Age_Group`, `Loan_Year`, `Loan_Quarter`, `Good_Bad_Flag`
- Built 5 pivot tables for initial EDA (state, branch, purpose, age, year)
- Used `VLOOKUP`, `IF`, `TEXT`, `YEAR()`, `MONTH()` functions throughout

Power BI (Desktop)
- Built an **8-page interactive dashboard** with drill-through and cross-filtering
- Wrote DAX measures: `QTD Loans`, `LY QTD Loans`, `Total Int rcvd`, `Total Pymnt inv`
- Used slicers for State, Year, and Branch — all pages respond in sync
- Designed KPI cards, gauge charts, donut charts, area charts, and bar charts

Tableau (Desktop / Public)
- Created a geographic heatmap of state-wise loan distribution across India
- Built story points for guided narrative walkthrough of key findings
- Used parameters and calculated fields for dynamic filtering
- Designed trend line charts and demographic breakdown vie
