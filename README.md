# SQL_Data_Warehouse_Project & Analytics_Project

## Overview
An end-to-end SQL Server Data Warehouse project that integrates CRM and ERP data, transforms raw data into business-ready datasets, and supports SQL analysis and BI reporting.

### Architecture
CRM / ERP → Bronze → Silver → Gold → Dashboard

- **Bronze:** Raw data loaded from CSV files.
- **Silver:** Data cleaning, validation, standardization, and transformation.
- **Gold:** Business-ready views organized using a Star Schema.
![Data_Architecture](https://github.com/OlanrewajuTheAnalyst/SQL_Data_Warehouse_Project/blob/main/1.png)

## Dataset
The project uses CRM and ERP CSV files containing:
- Customers
- Products
- Sales transactions
- Product categories
- Customer locations

## Tools
- Microsoft SQL Server
- SQL Server Management Studio (SSMS)
- T-SQL
- Stored Procedures
- SQL Views
- Star Schema
- Power BI / BI Reporting

## Key Steps
1. Created the `DataWarehouse` database and Bronze, Silver, and Gold schemas.
2. Loaded CRM and ERP CSV files into the Bronze layer using `BULK INSERT`.
3. Cleaned and transformed data in the Silver layer.
4. Integrated CRM and ERP customer and product information.
5. Created Gold-layer views:
   - `gold.dim_customers`
   - `gold.dim_products`
   - `gold.fact_sales`
6. Used SQL queries to analyze sales and customer/product performance.
7. Connected the Gold layer to a BI dashboard for reporting.

## Data Quality
Applied techniques including:
- Duplicate removal
- String cleaning
- Missing-value handling
- Data standardization
- Date validation
- Sales and price validation
- Surrogate key generation


## Results
Built a structured and reusable data warehouse that transforms raw CRM and ERP data into trusted data for **Business Analysts, Data Analysts, Data Scientists, and BI reporting**.

## How to Run
1. Install SQL Server and SSMS.
2. Clone the repository.
3. Run the database and table creation scripts.
4. Update the CSV file paths.
5. Run the Bronze and Silver loading procedures.
6. Create the Gold views.
7. Run the analysis queries or connect the Gold layer to Power BI.

## Skills

**SQL Server · T-SQL · Data Warehousing · ETL · Data Cleaning · Data Transformation · Data Integration · Stored Procedures · Star Schema · SQL Views · Power BI**

