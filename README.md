# Azure Data Factory Project: Airline & Revenue Analytics

This project demonstrates a **complete ETL and data orchestration workflow** in Azure Data Factory (ADF) using a hybrid architecture (cloud + on-premise).

---

## Project Overview

- **Objective:** Ingest, transform, and load data from multiple sources (API, SQL Server, File Server) into Azure Data Lake, transforming into Silver and Gold layers for analytics.
- **Architecture:** Medallion architecture (Bronze → Silver → Gold)
- **Key Features:**
  - API ingestion from GitHub and external sources
  - On-premise File Server integration via Self-Hosted IR
  - Azure SQL Database integration
  - Data transformation via Mapping Data Flows
  - Modular pipelines with parent-child orchestration
  - Incremental ingestion and data partitioning
  - Cloud storage: Azure Data Lake (ADLS Gen2)
  - Trigger-based automation (optional)

---

## Repo Structure
