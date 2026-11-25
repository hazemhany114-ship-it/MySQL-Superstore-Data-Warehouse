
# Superstore Data Warehouse | MySQL

## Project Overview

This project focuses on designing and implementing a data warehouse for the Sample Superstore dataset using MySQL.

The database is structured using the **Star Schema** dimensional modeling approach, organizing business data into fact and dimension tables to support efficient data retrieval, reporting, and analysis.

## Project Objectives

- Design a structured data warehouse using MySQL.
- Apply Star Schema dimensional modeling.
- Organize sales and returns data into fact tables.
- Separate descriptive business information into dimension tables.
- Build a database structure that supports SQL-based analysis and business intelligence.

## Database Design

The database follows the **Star Schema** dimensional modeling approach.

The following diagram illustrates the database structure and relationships between fact and dimension tables.

### Entity Relationship Diagram (ERD)

![Superstore Data Warehouse ERD](superstore-erd.png)

### Fact Tables

| Table | Description |
|---|---|
| `fact_sales` | Stores sales-related records. |
| `fact_returns` | Stores product return records. |

### Dimension Tables

| Table | Description |
|---|---|
| `dim_customer` | Customer-related information. |
| `dim_product` | Product-related information. |
| `dim_date` | Date-related information. |
| `dim_location` | Geographic and location information. |
| `dim_ship_mode` | Shipping mode information. |
| `dim_order` | Order-related information. |

## Tools & Technologies

- MySQL
- MySQL Workbench
- SQL
- Star Schema Data Modeling

## Repository Contents

| File | Description |
|---|---|
| `Superstore.sql` | SQL database export containing the database structure and data. |
| `README.md` | Project documentation. |

## Project Workflow

1. Database design and structure.
2. Fact and dimension table organization.
3. Star Schema implementation.
4. Database export and documentation.

---

**Project:** Sample Superstore Data Warehouse  
**Database:** `superstore_dw`  
**Technology:** MySQL
