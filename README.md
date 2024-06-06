# de_youtube_azure_project
Exploring opensource data and put it in azure cloud. Perform ELT

# Download file
Files are in kaggle: https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset

# Data Processing Workflow on Azure Platform
**1. Data Ingestion**
Tool Used: Azure Data Factory \
Description: Copy raw data from various sources into Azure Data Factory for centralized storage and initial processing.\
**2. Data Storage**
Tool Used: Azure Data Lake Storage Gen2
Description: Store the ingested data in Azure Data Lake Gen2, providing scalable and secure storage for large datasets. Additionally, paste cleaned data into a separate directory for easier use in future processes.
**3. Data Transformation and Preprocessing**
Tool Used: Azure Databricks
Description: Perform data transformation and preprocessing in Azure Databricks. This includes cleaning, aggregating, and preparing data for further analysis.
**4. Data Visualization**
Tool Used: Tableau
Description: Create intuitive and interactive dashboards in Tableau. Utilize the preprocessed data to generate insightful visualizations and reports
