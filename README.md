## AtliQ Hardware-Business Insights 360 FY-2018-2022

## Project Overview

AtliQ Hardware has seen significant growth in recent years and is now leveraging data analytics with Power BI to gain a competitive edge and make informed, data-driven decisions. This project aims to address various stakeholder questions across finance, sales, marketing, and supply chain sectors.

### Course Reference

This project is based on the techniques learned from the Codebasics Power BI Course. [Access the course here](https://www.example.com).

### Live Report

Check out the live Power BI report [here](https://app.powerbi.com/groups/me/reports/53de9a7c-bdb4-4a6d-b585-3f3cfb88eeaf/ReportSection?experience=power-bi).

## Tech Stack

- **SQL**
- **Power BI Desktop**
- **Excel**
- **DAX Language**
- **DAX Studio** (for report optimization)

## Project Charter

### Power BI Techniques Learned

- Asking key questions before project initiation
- Creating calculated columns
- Building measures with DAX language
- Effective data modeling
- Using bookmarks for visual navigation
- Page navigation with buttons
- Preventing zero-division errors with the `DIVIDE` function
- Creating date tables using M language
- Dynamic titles based on applied filters
- Implementing KPI indicators
- Conditional formatting with icons and background colors
- Data validation techniques

### Power BI Services

- Publishing reports to Power BI services
- Setting up personal gateways for automatic data refresh
- Creating Power BI apps
- Managing collaboration, workspaces, and access permissions

## GitHub

- Uploading large files using GitHub LFS
- Tracking specific file types with LFS

## Business Terminology

- **Gross Price**
- **Pre-Invoice Deductions**
- **Post-Invoice Deductions**
- **Net Invoice Sale**
- **Gross Margin**
- **Net Sales**
- **Net Profit**
- **COGS** - Cost of Goods Sold
- **YTD** - Year to Date
- **YTG** - Year to Go
- **Direct**
- **Retailer**
- **Distributors**
- **Consumer**

## Company Background

AtliQ Hardware has expanded significantly, operating globally and selling computers and accessories through three channels:

- **Retailers**
- **Direct**
- **Distributors**

Recently, the company faced losses from opening stores in America based on insufficient data analysis. To compete with rivals who have strong analytics teams, AtliQ Hardware is now building its own analytics team to drive future decisions with data.

## Project Kick-Off

### Key Questions Before Starting

1. What is the main objective of this Power BI dashboard?
2. How will the success of this project be measured?
3. What is the project's timeline?
4. Do stakeholders expect a preview before the final release?
5. What are the stakeholders' hopes for this project?
6. What are the stakeholders' concerns about this dashboard?
7. Who will use this dashboard and for what purpose?
8. What are the stakeholders' expectations for the completed project?
9. What potential issues might arise during the project?
10. What resources/data are needed for this dashboard?
11. Do stakeholders have any specific design or view preferences?

## Dataset Understanding

### Dimension Tables

- **dim_customer**: Contains static data such as customer and product details across 27 markets, 75 customers, and two platforms (Brick & Mortar, E-commerce).
- **dim_market**: Details 27 markets, 7 sub-zones, and 4 regions (APAC, EU, nan, LATAM).
- **dim_product**: Includes product divisions, categories, and variants.

### Fact Tables

- **fact_forecast_monthly**: Forecasted customer needs to enhance satisfaction and reduce warehouse costs.
- **fact_sales_monthly**: Similar to `fact_forecast_monthly` but includes actual sold quantities.

### Additional Tables

- **freight_cost**: Travel and other costs per market per fiscal year.
- **gross_price**: Gross prices with product codes.
- **manufacturing_cost**: Manufacturing costs with product codes per year.
- **pre_invoice_deductions**: Pre-invoice deduction percentages per customer per year.
- **post_invoice_deductions**: Post-invoice deductions and other details.

## Data Import into Power BI

Connect to the MySQL database and import datasets into Power BI using the provided database credentials.

## Data Modeling

Effective data modeling is crucial for performance and accuracy. We followed the Snowflake schema for this project.

## Dashboard Design

Create visuals based on mock-ups and develop measures as needed. Key views include:

- **Home View**: Navigation buttons to specific pages.
- **Info Page**: Overview and project details.
- **Finance View**: Financial metrics and insights.
- **Sales View**: Sales performance and trends.
- **Marketing View**: Marketing effectiveness metrics.
- **Supply Chain View**: Logistics and supply chain insights.
- **Executive View**: High-level executive summary.
- **Products**: Detailed product information.

### Visuals and Interactions

- **Home View**: Central navigation hub.

  
  ![Dash Board Preview](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZDJocjlteWxiM2p1aGNqaDVnNWU3cmR5bzNqd3d0NnhkY2F4cXg4aiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/5Kcnnpj81dPDN5cXRi/giphy.gif)


- **Info View**:

 
  ![Dash Board Preview](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWZyOHZmaWJtNTRsZmdiZWloZ3NudWU2N282bWpvMWF3MWpobndjYiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/RisEy1Dux44Z1sI0Bw/giphy.gif)
- **Finance View**: In-depth financial analysis.


   ![Dash Board Preview](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExeWFteHRoNWdybmNvZmdpcXY2OTdsOHR1eW02cDZpYXd2enVwMGVleCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3mKu2nH9rdQP9EiPo6/giphy.gif)
- **Sales View**: Comprehensive sales data.


 ![Dash Board Preview](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExbHozbmgwcTk5d3VkdnBhamhkanFsbXVtczFpMm50enE5Yng3dzhhdyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/jBQKB2E16hcgGuaKFd/giphy.gif)
- **Marketing View**: Marketing metrics and analysis.


 ![Dash Board Preview](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExaGo4MGVuNG1nZmtpa3djNjNoNXlyZ2xmNzAyNTF3dHRrNGYzZTdpaSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/AOY2No0cgntf1z8TIU/giphy.gif)
- **Supply Chain View**: Supply chain insights.


![Dash Board Preview](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExaGxvMHgzYXJoNHFoM254bnk0ZzJhOWwwZTl2MHp3enh0bjdlNHFpMSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/5yme9iegIhZEZ5tGlv/giphy.gif)
- **Executive View**: Executive summary and key metrics.


![Dash Board Preview](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExYjh1YWg0Zm40MGF5Y3dia20zMDhsMHprcWR6eWZoZzA0dWt1cTdhZSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/kIaTNwaycppwjlRL2X/giphy.gif)

- **Support View**: 


![Dash Board Preview](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExMTN6cnFxNzluZ2Q1bHpjc3E1YjVxbjA4YjVscW5pNzJ5eWhrNWx5MiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/xp2Q7BMBzTantebqfd/giphy.gif)

## Project Outcome

This comprehensive report enables informed, data-driven decisions, answering various stakeholder questions and improving business strategy.

## Video Recordings

Watch Clip of the Power BI files.



![Dash Board Preview](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZjljeTJzZDBsb2t5N2Y2bzlsM2owcmh5N2xqdnhpZXlxODVkYXUzeCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/gQUp22MHSYTlrkr4XF/giphy.gif)


