# NYC Taxi Azure Data Engineering Project

## Overview
This repository contains an **end-to-end data engineering project** on the NYC Taxi dataset using Azure, Databricks, Delta Lake, and Power BI.  
The project follows a **medallion architecture** (Bronze → Silver → Gold) and demonstrates real-world data engineering practices suitable for portfolio and interview presentations.

**Key highlights:**
- Automated ingestion of NYC Taxi Parquet files via Azure Data Factory (ADF)
- Clean, transform, and store data using Azure Databricks and PySpark
- Delta Lake for versioning, ACID transactions, and time travel
- Business-ready tables exposed to Power BI for analytics and dashboards

---

## Folder Structure

Nyc_Taxi_Azure_Project/
│
├── Notebooks/
│ ├── Bronze Notebook.ipynb
│ ├── Silver Notebook.ipynb
│ └── Gold Notebook.ipynb
│
├── Data/
│ ├── taxi_zone_lookup.csv
│ └── trip_type.csv
│
├── PowerBI/
│ └── NYC_Taxi_Dashboard.pbix
│
└── README.md

