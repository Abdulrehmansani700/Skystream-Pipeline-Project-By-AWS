# SkyStream AWS Data Pipeline Project

A professional End-to-End Data Engineering pipeline built on AWS to process, analyze, and visualize retail data (Superstore Dataset).

## 🚀 Architecture Overview
The pipeline follows a modern cloud data stack approach:
1. **Data Source:** Local CSV files.
2. **Ingestion:** Python (Pandas) for ETL and Boto3 for uploading data to **Amazon S3**.
3. **Data Cataloging:** **AWS Glue Crawler** automatically scans S3 buckets to create a Data Catalog.
4. **Data Querying:** **Amazon Athena** is used to run SQL queries directly on the S3 data.
5. **Visualization:** **AWS QuickSight** for building interactive business intelligence dashboards.


## 🛠️ Tech Stack
* **Language:** Python (Pandas, Boto3)
* **Cloud:** Amazon Web Services (AWS)
* **Services:** S3, AWS Glue, Amazon Athena, QuickSight
* **IDE:** VS Code / Jupyter Notebook

## 📁 Project Structure
* `Python File Pipeline/`: Contains the ETL and S3 upload scripts.
* `Dataset file CSV/`: Raw and cleaned data files.
* `Architecture Of Dataflow Project/`: Technical diagrams of the pipeline.

## ⚙️ How to Run
1. **ETL & Upload:** Run the Python script to clean the `Superstore.csv` and upload it to your S3 bucket.
2. **Crawler:** Run the AWS Glue Crawler to populate the metadata in the Glue Data Catalog.
3. **Analyze:** Use Amazon Athena to perform SQL analysis on the generated tables.
4. **Visualize:** Connect QuickSight to Athena to create visual reports.

---
**Note:** *Ensure your AWS CLI is configured or environment variables are set before running the Python scripts.*
