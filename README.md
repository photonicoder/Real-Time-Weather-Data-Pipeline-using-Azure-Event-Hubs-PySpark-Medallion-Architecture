# Real-Time-Weather-Data-Pipeline-using-Azure-Event-Hubs-PySpark-Medallion-Architecture

#Project Overview:
Developed and deployed a real-time weather data processing pipeline leveraging Azure Event Hubs for ingestion, PySpark on Databricks for transformation, and Delta Lake on ADLS Gen2 for efficient storage following the Medallion Architecture (Bronze, Silver, Gold layers).

Key Responsibilities:
✅ Ingested Real-Time Data from the Weather API every 5 minutes using Python and published events to Azure Event Hubs.
✅ Streamed Data into Databricks by reading from Event Hubs using Structured Streaming in PySpark.
✅ Implemented Medallion Architecture:

Bronze Layer: Raw data ingestion from Event Hubs into Delta Lake (ADLS Gen2).
Silver Layer: Cleaned, transformed, and enriched data using PySpark.
Gold Layer: Aggregated and optimized data for analytics and reporting.
✅ Optimized Data Processing using Z-Ordering, Data Skipping, and Auto Loader.
✅ Ensured Fault Tolerance with Checkpointing, Write-Ahead Logging (WAL), and Idempotent Writes.
✅ Implemented Schema Handling to accommodate schema drift and changes dynamically.
✅ Enabled Data Access for downstream analytics, dashboards, and machine learning workloads.
Achievements:
