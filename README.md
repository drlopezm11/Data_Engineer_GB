# Azure Data Pipeline: Blob Storage to SQL Server

## Overview
This project automates the process of transferring CSV files from Azure Blob Storage to an Azure SQL Database using **Azure Data Factory (ADF)**

## Architecture
- **Azure Blob Storage**: Stores incoming CSV files.
- **Azure Data Factory (ADF)**: Orchestrates data movement and transformation.
- **Azure SQL Database**: Stores the processed data.
- **Event Grid Trigger : Detects new file uploads and triggers the pipeline.

## Features
- **Automated File Processing**: Iterates over all CSV files in a given folder.
- **Dynamic Table Creation**: Automatically creates tables in SQL Server based on CSV file names.
- **Data Cleansing & Transformation**: Converts data types and formats.
- **Error Handling**: Logs failures for troubleshooting.
- **Security**: Implements role-based access control for SQL users.

---

