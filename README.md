# F1-Data-Analysis

This project is based on azure data engineering. Main goal is to first ingest the data in azure data lake gen2, Transform that data using spark and databricks and finally 
loading that data into presentation layer for visualization using PowerBI

## Business Requirements 
- Find dominant formula 1 drivers
- Find dominant Teams in formula 1
- Schedule the pipeline to run every sunday 10PM
- Ingesting logic must be able to handle incremental data

## Technologies Used
- Pyspark ( Data analysis)
- Spark SQL
- Azure Databricks
- Azure Data lake gen2
- Azure Data Factory (Pipeline Scheduling)
- Azure key- Vault
- Power BI (Visualizations)
