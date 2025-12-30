# NYC Taxi Azure Data Engineering Project

## Overview
This repository contains an **end-to-end data engineering project** on the NYC Taxi dataset using Azure, Databricks, Delta Lake, and Power BI.  
The project follows a **medallion architecture** (Bronze → Silver → Gold) and demonstrates real-world data engineering practices suitable for portfolio and interview presentations.

**Key highlights:**
- Automated ingestion of NYC Taxi Parquet files via Azure Data Factory (ADF)
- Clean, transform, and store data using Azure Databricks and PySpark
- Delta Lake for versioning, ACID transactions, and time travel
- Business-ready tables exposed to Power BI for analytics and dashboards
