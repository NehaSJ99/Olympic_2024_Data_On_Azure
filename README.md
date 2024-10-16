# Paris 2024 Olympics Data Pipeline

This project focuses on ingesting, transforming, and analyzing data related to the Paris 2024 Olympics using cloud-based technologies. The architecture leverages Azure services for data processing and analytics, with final visualizations in Power BI, Looker Studio, and Tableau.

## Architecture Overview

### 1. **Data Source**
   - The raw data is collected from various sources related to the Paris 2024 Olympics.

### 2. **Data Integration**
   - **Azure Data Factory** is used for orchestrating and automating data movement from the data source to storage.

### 3. **Raw Data Store**
   - The ingested data is stored in **Azure Data Lake Gen 2** for raw data storage.

### 4. **Data Transformation**
   - The raw data is processed and transformed using **Azure Databricks**, where cleaning, filtering, and data transformation logic is applied.

### 5. **Transformed Data Storage**
   - The transformed data is again stored in **Azure Data Lake Gen 2** for further processing.

### 6. **Data Analytics**
   - **Azure Synapse Analytics** is utilized for running analytical queries on the transformed data to extract insights and trends.

### 7. **Dashboards & Visualization**
   - Visualizations and dashboards are created using:
     - **Power BI**
     - **Looker Studio**
     - **Tableau**

## Tools and Technologies

- **Azure Data Factory**: Data integration and orchestration.
- **Azure Databricks**: Data transformation and processing.
- **Azure Data Lake Gen 2**: Data storage (raw and transformed).
- **Azure Synapse Analytics**: Data analytics platform for querying and insights.
- **Power BI / Looker Studio / Tableau**: Dashboard and visualization tools for presenting the final data insights.

## Project Goals

- Ingest and store Paris 2024 Olympics data in a scalable cloud environment.
- Transform and clean the data for meaningful insights.
- Perform advanced analytics to explore trends and metrics.
- Visualize key insights using interactive dashboards.

## Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/NehaSJ99/Olympic_2024_Data_On_Azure.git
