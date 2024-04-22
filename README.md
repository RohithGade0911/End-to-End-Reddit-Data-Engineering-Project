# End-to-End-Reddit-Data-Engineering-Project

## Project Overview
This project provided a robust data pipeline to extract, transform, and load (ETL) Reddit data into an Amazon Redshift data warehouse, facilitating deep analysis and insights.

## Technologies Used
- **Apache Airflow & Celery**: Used for task scheduling and workflow management.
- **PostgreSQL**: Served as the initial data storage and management system.
- **Amazon S3**: Utilized for data staging and storage.
- **AWS Glue & Amazon Athena**: Employed for data transformation and querying.
- **Amazon Redshift**: Used for data warehousing.

## Project Flow
1. **Data Extraction**: Data was fetched from Reddit using specified tools.
2. **Data Staging**: Data was initially stored in PostgreSQL, then staged in Amazon S3.
3. **Data Transformation**: AWS Glue and Amazon Athena were used to transform data for analysis.
4. **Data Loading**: Transformed data was loaded into Amazon Redshift for querying.
5. **Workflow Management**: Tasks were managed with Apache Airflow and Celery.

## Architecture
![Architecture Diagram](https://github.com/RohithGade0911/Reddit-Data-Pipeline-Project/blob/main/Architecture.png "Project Architecture")

