# Big-Data-ETL-Pipeline-for-NOAA-Weather-Data

## Overview
This project demonstrates the use of **Apache Spark with PySpark** to read, process, and analyze data stored in an **S3-compatible object storage system (MinIO)**. The notebook focuses on configuring Spark to connect to external storage, performing data ingestion, transformation, and validation, and handling real-world distributed data processing scenarios commonly used in modern data engineering workflows.

---

## Objectives
- Configure Apache Spark to connect to S3-compatible object storage  
- Read data from object storage into Spark DataFrames  
- Perform data validation and transformations using PySpark  
- Handle missing files and runtime exceptions gracefully  
- Understand distributed data access patterns in Spark  

---

## Technologies Used
- Apache Spark  
- PySpark  
- Python 3  
- S3-Compatible Object Storage (**MinIO**)  
- Hadoop AWS Connector (S3A)  
- Jupyter Notebook  
- Linux Environment  

> **Note:** MinIO is used as an S3-compatible storage layer, and Spark accesses it using standard `s3a://` APIs, similar to AWS S3.

---

## Architecture Overview
1. Spark is configured with Hadoop S3A settings.  
2. Access credentials are supplied through Spark configuration.  
3. Data is read from an S3-compatible bucket (MinIO).  
4. Spark DataFrames are used for processing and validation.  
5. Errors such as missing or inaccessible files are handled explicitly.  

---

## Key Features
- Spark configuration for S3-compatible storage access  
- Secure handling of access credentials  
- Distributed data loading using `s3a://` paths  
- Exception handling for missing files  
- Scalable data processing using Spark DataFrames  

---
