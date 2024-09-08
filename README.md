# AdventureWorks's Sales Insights Data Analysis

## Business Demand Overview
- Reporter: Stephen (Sales Manager)
-	Value of Change: Visual dashboards and improved Sales reporting or follow up or sales force
-	Necessary Systems: Power BI, CRM System
-	Other Relevant Info: Budgets have been delivered in Excel for 2024

### User Stories
| **No** | **As a (role)** | **I want (request/demand)** | **So that I (user value)** | **Acceptance Criteria** |
| --- | --- | --- | --- | --- |
| **1** | Sales Manager | To get a dashboard overview of internet sales | Can follow better which customers and products sells the best | A Power BI dashboard which updates data once a day |
| **2** | Sales Manager | A dashboard overview of internet sales | Follow sales over time against budget | A Power BI dashboard with graphs and KPIs comparing against budget. |
| **3** | Sales Representative | A detailed overview of Internet Sales per Customers | Can follow up my customers that buys the most and who we can sell ore to | A Power BI dashboard which allows me to filter data for each customer |
| **4** | Sales Representative | A detailed overview of Internet Sales per Products | Can follow up my Products that sells the most | A Power BI dashboard which allows me to filter data for each Product |

### Data Sources
- All Sales data is stored in SQL Server.
- SalesBudget is a excel file that was sent over.
### Nescessary tables:
  - FactInternetSales
  - DimCustomer
  - DimProduct
  - DimDate
  - SalesBudget
### Data Praparation
1. Extract - Transfrom - Load (ETL)  
Use SQL scripts to ETL necessary shaped tables
2. Data Profiling
3. Data Cleaning
  

   
  



