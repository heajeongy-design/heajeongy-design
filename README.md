## Introduce

I'm a **Data Engineer** working with data pipelines, lakehouse/DW platforms, and BI systems.
I focus on explaining **why** a design was chosen and **proving** it with reproducible checks.

### Projects

| Project | What it is | Stack |
|---|---|---|
| **[ecommerce-order-lifecycle-iceberg](https://github.com/heajeongy-design/ecommerce-order-lifecycle-iceberg)**<br>Personal project | Order lifecycle events → Kafka → Spark batch → S3 Bronze → Iceberg Silver/Gold, queried with Glue/Athena. Airflow runs a 15-min pipeline and daily Iceberg maintenance (health checks, conditional OPTIMIZE, VACUUM). | `Kafka` `Spark` `Iceberg` `S3` `Glue` `Athena` `Airflow` `Docker` |
| **[fabric-manufacturing-lakehouse](https://github.com/heajeongy-design/fabric-manufacturing-lakehouse)**<br>Work · 2026.03 – 2026.06 | Manufacturing data platform on Microsoft Fabric: metadata-driven ingestion, Bronze/Silver/Gold marts, Power BI. Includes a fan-out bug fix and a local PySpark + Delta reproduction verified in CI. | `Microsoft Fabric` `PySpark` `Delta Lake` `T-SQL` `Power BI` |
| **[synapse-dw-maintenance-cases](https://github.com/heajeongy-design/synapse-dw-maintenance-cases)**<br>Work · 2025.12 – 2026.03 | Maintenance of a running Azure Synapse sales DW: root-cause analysis of a Refresh OOM (duplicated DIM → join explosion), missing master data, schema inference failure, runtime upgrade refactoring. Each case reproduced locally. | `Azure Synapse` `Dedicated SQL Pool` `AAS` `PySpark` `Power BI` |

Company names in work projects are anonymized. No company data or credentials are included.

### Experience

**IT Solution Company — Data Engineer**

* Data Engineering & BI projects (Microsoft Fabric, Azure Synapse)
* ETL/ELT pipelines and data processing
* Data modeling and BI dashboard development

**Coupang Fulfillment Services — RP (Research & Planning)** `2024.08 – 2025.11`

* Data analysis & KPI management
* Power BI dashboard development
* Operational process improvement

### Tech Stack

| Area | |
|---|---|
| Language | `SQL` `Python` |
| Data Engineering | `ETL/ELT` `Apache Kafka` `Apache Spark` `Apache Airflow` `Docker` |
| Table Format | `Apache Iceberg` `Delta Lake` |
| Cloud & Data Platform | `AWS (S3, Glue, Athena, Lambda)` `Azure Synapse` `Microsoft Fabric` |
| Database | `SQL Server` `MySQL` `PostgreSQL` |
| BI & Microsoft Data Stack | `Power BI` `SSIS` `SSAS / Azure Analysis Services` |
| Tools | `Git` `GitHub Actions` `Visual Studio` `Tabular Editor` |

### Currently Learning

`Lakehouse Operations` `Distributed Data Processing` `Data Pipeline Architecture`

### Goal

Build and operate end-to-end data systems:
**Data Ingestion → ETL/ELT → Data Warehouse/Lakehouse → BI & Analytics**

### Contact

**Email:** gowjd6408@naver.com
