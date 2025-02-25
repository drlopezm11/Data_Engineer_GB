# Globant Data Enginieer
## Overview
This project automates the process of transferring CSV files from Azure Blob Storage to an Azure SQL Database using **Azure Data Factory (ADF)**

## Architecture
- **Azure Blob Storage**: Stores incoming CSV files.
- **Azure Data Factory (ADF)**: Orchestrates data movement and transformation.
- **Azure SQL Database**: Stores the processed data.
- **Event Grid Trigger : Detects new file uploads and triggers the pipeline.

---

