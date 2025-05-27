# Azure Car Sales Data Pipeline

![Azure Data Pipeline Architecture](images/image.png)

An end-to-end data engineering solution automating car sales data processing and reporting using Microsoft Azure's data ecosystem.

## 📌 Project Overview

Built a scalable data pipeline implementing the medallion architecture pattern to transform raw car sales data into actionable business insights. The solution handles data ingestion, transformation, and serving with Azure Data Factory, Databricks, and Power BI.

## 🛠️ Technical Stack

**Azure Services:**
- Azure Data Factory (Orchestration)
- Azure Databricks (Transformation)
- Azure Data Lake Gen2 (Storage)
- Delta Lake (Data Format)
- Unity Catalog (Governance)

**Languages & Tools:**
- PySpark (Data Processing)
- SQL (Data Modeling)
- Python (Scripting)
- Power BI (Visualization)

## 📂 Project Structure

```plaintext
├── data_factory/            # ADF pipeline definitions
├── databricks/              # Notebooks for data transformation
│   ├── bronze_to_silver.py  # Initial cleansing
│   ├── silver_to_gold.py    # Business transformations
│   └── utilities/           # Helper functions
├── sql/                     # Database schemas
├── powerbi/                 # Dashboard definitions
└── docs/                    # Architecture diagrams
