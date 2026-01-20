# Big-Data-ETL-Pipeline-for-NOAA-Weather-Data

## Overview
This project contains a Jupyter Notebook (`module9.ipynb`) that demonstrates large-scale data processing using **Apache Spark (PySpark)**. The notebook focuses on reading external data sources, performing structured transformations, applying schema definitions, and writing processed results using Spark’s DataFrame and SQL APIs.

The implementation follows best practices for distributed data processing, including schema enforcement, column transformations, and efficient I/O operations.

---

## Technologies Used
- **Apache Spark (PySpark)**
- **Python 3**
- **Jupyter Notebook**
- **Spark SQL & DataFrame API**
- **Distributed file/object storage (e.g., MinIO / filesystem)**
- **Parquet format**

---

## Key Features
- Spark session initialization with custom configuration
- Reading raw data into Spark DataFrames
- Explicit schema definition for structured data
- Data cleaning and transformation using Spark SQL functions
- Column extraction and formatting
- Writing processed data to Parquet for efficient storage
- Error handling for missing or inaccessible data sources

---

## Project Structure
