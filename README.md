# 🚀 Sales Analytics Pipeline using dbt + SQL + Snowflake

*Transforming raw e-commerce sales data into analytics-ready reports using dbt and SQL.*

## 📌 Project Overview

A mini data warehouse implementation for e-commerce analytics:
- Ingests raw CSV data (orders, customers, products)
- Loads into Snowflake/PostgreSQL data warehouse
- Transforms data using dbt into clean dimensional models
- Generates actionable insights (monthly sales, customer segmentation, product performance)

## 🛠️ Tools Used
- **Data Warehouse**: Snowflake
- **Transformation**: dbt (data build tool)
- **Version Control**: GitHub
- **CI/CD**: GitHub Actions 

## 📂 Project Structure

SALES_ANALYSIS_PROJECT/
├── .vscode/
├── analyses/
├── dbt_packages/
├── logs/
├── macros/
├── models/
│   ├── staging/
│   └── marts/
│       └── sales_summary.sql
├──snowflakesample/
│       ├── schema.yml
│   ├── stg_customers.sql
│   ├── stg_orders.sql
│   └── stg_products.sql
├── seeds/
├── snapshots/
│   └── .gitkeep
├── target/
├── tests/
├── .gitignore
├── dbt_project.yml
└── README.md
