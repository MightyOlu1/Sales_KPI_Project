Sales Analytics Project – Azure Data Engineering

Overview

A modern sales data engineering workflow using Azure Data Factory, Azure Databricks, and Azure Data Lake Storage, following the medallion architecture (Bronze → Silver → Gold) to transform raw data into business-ready insights. Optional visualization is supported via Power BI.

Features

Data Ingestion: Pull raw sales data from multiple sources with ADF pipelines.

Data Transformation: Clean, enrich, and aggregate data using Databricks & PySpark.

Data Storage: Store processed data in Azure Data Lake Storage Gen2 or Azure SQL Database.

Analytics & Reporting: Generate dashboards and insights with Power BI.

Automation: Orchestrate pipelines and workflows for seamless data processing.

Architecture

Bronze Layer: Raw data ingestion

Silver Layer: Cleaned and enriched datasets

Gold Layer: Aggregated, business-ready datasets

Optional: Add a diagram showing the flow: Sources → Bronze → Silver → Gold → Analytics

Usage

Run ADF pipelines to ingest raw sales data into the Bronze layer.

Execute Databricks notebooks to clean, enrich, and aggregate data.

Explore datasets in Azure SQL Database or visualize insights in Power BI using the Gold layer.
