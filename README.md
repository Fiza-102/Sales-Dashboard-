# SALES-DASHBOARD

## Table of Contents
- [Purpose](#purpose)
- [Build Data Source](#builddatasource)
- [Analysing Requirements and choosing right chart](#choosingrightchart)
- [Prerequisites](#Prerequisites)
- [Data Filters](#DataFilters)
- [Dashboard](#Dashboard)

### Making it dynamic and adding buttons to switch from sales dashboard to customer dashboard.

## Purpose
To present an overview of sales metrics and trends in order to analyse year-over-year sales performance and understand sales trends.
Building dashboard to help stakeholders, including salesmanager and executives to analyse sales performance.



## Build Data Source
- Connecting to sales data : orders.csv, customers.csv, location.csv, product.csv.
- Creating Data Model using Relationship between above files where orders will be fact and other files are dimension.
- Rename Fields and Tables.
- Check Data types.

## Analysing Requirements and choosing right chart

1. KPI OVERVIEW  [using KPI BANS]
   - Display summary of Total Sales, Profit, Quantity for current year and previous year.
     
2. SALES TRENDS [using SPARKLINE]
   - Present data for each KPI on monthly basis for CY and PY.
   - Identify months with highest and lowest sales/profit/quantity and make them easy to recognize respectively.
     
3. PRODUCT SUBCATEGORY COMPARISON [using Bar-IN-Bar]
   - Compare sales performance by different product subcategory for current year and previous year.
   - Include a comparison of sales with profit

4. WEEKLY TRENDS FOR SALES AND PROFIT [using StepChart]
   - Present weekly sales & profit data for current year.
   - Display average weekly values.
   - Highlight weeks that are above and below avg to draw attention to sales and profit performance.
     

## Prerequisites
Tableau Public, Interactive parameters, ,Adding Filter actions, navigate buttons

## Data Filters
 Allow users to filter data by product information(category, subcategory) and by Location info (region, state, city).
 
 
## Dashboard
![LINK to DASHBOARD](=https://public.tableau.com/views/SALESDASHBOARD_17214015441040/SalesDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
