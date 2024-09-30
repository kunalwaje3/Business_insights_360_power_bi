# Business_insights_360_power_bi
# Project Overview

AtliQ Hardware is growing rapidly in the recent years, and they have decided to implement data analytics using Power BI in their company for the first time to surpass their competitors in the market and make data-driven decisions. This project is hoped to give answers to the questions of stakeholders in terms of all aspects like finance, sales, marketing, and supply chain.

I worked on this project by following the Codebasics Power BI Course. **[Live Report Link](https://app.powerbi.com/view?r=eyJrIjoiYzc3MGU4MjctYmI2Yy00Y2EyLWE3YWUtOGM3MzY3NmMxZTA5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)**

---

## Tech stacks

- SQL
- Power BI Desktop
- Excel
- DAX language
- DAX studio (for optimizing the report)
- Project charter file

---

## Power BI Techniques Learnt

- Asking key questions before starting the project
- Creating calculated columns
- Creating measures using DAX language
- Data modeling
- Using Bookmarks to switch between visuals
- Page navigation with buttons
- Using the divide function to prevent zero division errors
- Creating a date table using M language
- Dynamic titles based on the applied filters
- Using KPI indicators
- Conditional formatting in visuals using icons or background color
- Data validation techniques
- Power BI services
- Publishing reports to Power BI services
- Setting up a personal gateway for auto-refresh of data
- Power BI App creation
- Collaboration, workspace, access permissions in Power BI services
- And more 😅

---

## Business-related Terms

- Gross price
- Pre-invoice deductions
- Post-Invoice deductions
- Net Invoice sale
- Gross Margin
- Net sales
- Net profit
- COGS - Cost of Goods Sold
- YTD - Year to Date
- YTG - Year to Go
- Direct, Retailer, Distributors, Consumer

---

## Company's Background

AtliQ Hardware is a company that has grown vastly in recent years, opening business globally. It sells computer and computer accessories through three channels:

- Retailers
- Direct
- Distributors

Recently, the company faced unforeseen losses by opening stores in America based on surveys, intuition, and some Excel analysis. Also, competitors have analytics teams performing data-driven decisions. To survive in the industry, AtliQ Hardware has decided to build an analytics team.

---

## Key Questions Before Starting the Dashboard

- What is the objective of building this Power BI dashboard?
- How will the success of this project be measured?
- What is the project's deadline?
- Do stakeholders expect a preview before the actual release?
- What are the stakeholders' hopes and fears for this project?
- Who will use this dashboard, and for what purpose?
- What can go wrong while building the project?
- What resources/data are needed for this dashboard?
- Any input from stakeholders regarding design and views of the dashboard?

---

## Dataset Understanding

### Dimension Table: 
It has static data like details of customers and products.

### Fact Table: 
It contains data about transactions.

---

### gdb041:

- **dim_customer:** 
  - 27 distinct markets (e.g., India, USA, Spain)
  - 75 distinct customers
  - 2 platforms: Brick & Mortar (Physical stores), E-commerce (Online stores)

- **dim_market:**
  - 27 distinct markets, 7 sub-zones, 4 regions: APAC, EU, NAN, LATAM

- **dim_product:** 
  - Divisions: P & A, Peripherals, Accessories, PC, Networking, Storage
  - Categories: Internal HDD, Keyboard, etc.
  - Product variants

- **fact_forecast_monthly:**
  - Forecast customer needs, higher satisfaction, reduced storage cost

- **fact_sales_monthly:**
  - Similar to the forecast table but with sold quantities

---

### gdb056:

- **freight_cost:** 
  Travel and other costs for each market

- **gross_price:** 
  Gross prices by product code

- **manufacturing_cost:** 
  Manufacturing costs by product code and year

- **Pre_invoice_deductions:** 
  Pre-invoice deduction percentages per customer and year

- **Post_invoice_deductions:** 
  Post-invoice deductions and other deductions
