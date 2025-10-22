# Excel — Retail Sales Dashboard

**Tools:** Excel for the Web (free)  
**Dataset:** retail_sales.csv (320 rows, 2023)  
**Goal:** Build an interactive one-page dashboard for regional, monthly, and product performance.

---

## What I Built
- Structured data table (`SalesTbl`) with calculated columns: `YearMonth`, `NetSales`, `DaysToShip`
- 3 PivotTables + Charts:
  - Sales by Region
  - Revenue Trend by Month
  - Top Products by Revenue
- Slicers for Region, Category, OrderPriority, YearMonth
- KPI card: Total Revenue

---

## Steps
1. Imported CSV and formatted as Table (`SalesTbl`)
2. Added calculated columns  
   - `YearMonth = TEXT([@OrderDate],"yyyy-mm")`  
   - `NetSales = [@Quantity]*[@UnitPrice]*(1-[@Discount])`  
   - `DaysToShip = [@ShipDate]-[@OrderDate]`
3. Created PivotTables + charts and connected slicers  
4. Designed one-page dashboard and added KPI cards

---

## Key Insights
- **Top Region:** East (~$233 K)  
- **Top Products:** Chair, Monitor, Table  
- **Revenue Trend:** Peaks in March & December  
- **Total Revenue:** $789 473  

---

## Files
- retail_sales.csv  
- Sales_Dashboard_Screenshot.png  
- Sales_Dashboard.xlsx  

*Created as part of my hands-on analytics learning journey.*
