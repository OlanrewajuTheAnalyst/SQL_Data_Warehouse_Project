# SQL_Data_Warehouse

## 🎯 Overview
An end-to-end SQL Server Data Warehouse integrating CRM and ERP data, transforms raw data into business-ready datasets, and supports SQL analysis and BI reporting.

This work demonstrates ETL, data cleaning, data integration, dimensional modeling, and analytical SQL, with the final Gold layer designed for BI reporting.

### 🏗️ Architecture    
CRM / ERP → Bronze → Silver → Gold → Dashboard

- **Bronze:** Raw data loaded from CSV files.
- **Silver:** Data cleaning, validation, standardization, and transformation.
- **Gold:** Business-ready views organized using a Star Schema.
![Data_Architecture](https://github.com/OlanrewajuTheAnalyst/SQL_Data_Warehouse_Project/blob/main/1.png)

### 🎯 What I Built
- Integrated CRM and ERP datasets covering customers, products, sales, and locations.
- Built a three-layer data warehouse architecture: Bronze, Silver, and Gold.
- Developed ETL processes using T-SQL and Stored Procedures.
- Cleaned, standardized, and validated raw data.
- Integrated customer and product information from multiple sources.
- Designed a Star Schema with:
   - gold.dim_customers
   - gold.dim_products
   - gold.fact_sales
- Created SQL views and analytical queries for sales, customer, and product analysis.
- Connected the Gold layer to Power BI for reporting.

  ## 📈 Data Quality
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

## 🛠️ Skills Demonstrated
**SQL Server · T-SQL · Data Warehousing · ETL · Data Cleaning · Data Transformation · Data Integration · Stored Procedures · Star Schema · SQL Views · Power BI**

