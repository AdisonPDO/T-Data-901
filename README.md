# Crypto Viz Project README
## Introduction
Welcome to the "Crypto Viz" project. This activity encourages you to explore and manipulate large datasets using a variety of technologies such as Pandas, DuckDB, and Apache Spark.

### Prerequisites
You will need the files available on the SharePoint site related to this module.

### Installation
Pandas: A tool offering fast, flexible, and expressive data structures.
```pip install pandas```
Use the pandas.read_csv function to open and analyze the large Liquor_Sales.csv file.

### DuckDB: An in-process DBMS.
```pip install duckdb==0.8.0```
Utilize it to explore data and to import and export to a parquet file as demonstrated in the provided code snippet.

### Apache Spark: A unified engine for large-scale data analytics.

Follow the steps outlined in the script to set up your custom Spark cluster with Docker and run a simple word count application on your cluster.

## Usage
### DuckDB
```import duckdb as ddb
con = ddb.connect("my-working-database.db")
# ... (Refer to the initial code for complete steps)
```
## Apache Spark
Create your custom network and Spark cluster master as indicated, then follow the steps to run a simple word count example on your cluster.
