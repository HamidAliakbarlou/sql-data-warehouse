# 📊 Data Warehouse and Analytics Project

This portfolio project demonstrates an end-to-end modern data warehousing and analytics solution, showcasing industry best practices in **ETL, data modeling, and reporting** using SQL Server.

---

## 🏗️ Project Architecture: Medallion Design

This project implements a **Medallion Architecture** with three structured layers:

- **Bronze Layer**: Raw data ingestion from ERP and CRM CSV files into SQL Server. No transformations.
- **Silver Layer**: Data cleaning, deduplication, standardization, and normalization for improved data quality.
- **Gold Layer**: Business-ready star schema models (fact & dimension tables) optimized for analytics and reporting.

---

## 📌 Project Goals

**Data Engineering Objectives**:
- Build a scalable SQL Server-based data warehouse.
- Develop modular ETL pipelines for ERP and CRM datasets.
- Design a clean and query-optimized star schema.
- Document data models and architecture clearly for business and technical users.

**Data Analytics Objectives**:
- Deliver SQL-based reports and KPIs focused on:
  - 🔍 Customer behavior
  - 📦 Product performance
  - 📈 Sales trends

The result: actionable business insights to support strategic decisions.

---

## 💡 Tools & Technologies Used

| Tool                  | Purpose                                     |
|-----------------------|---------------------------------------------|
| **SQL Server Express**| Lightweight database engine                 |
| **SSMS**              | SQL development and query interface         |
| **Draw.io**           | Architecture, ETL, and data model diagrams |
| **GitHub**            | Code versioning and project documentation   |
| **Notion**            | Project task management and planning        |

---


## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
```



## 👨‍💻 What I Learned from This Project

- Building a SQL data warehouse using a layered architecture
- Writing efficient ETL pipelines using SQL
- Designing scalable star schemas for BI
- Creating clear and reusable documentation
- Applying analytics to generate business insights

---

## 📎 Project Scope

- 📁 Source: Two systems (ERP + CRM)
- 🧹 Focus: Clean and integrate most recent data only
- 📊 Output: Star schema with business-ready tables for insights


