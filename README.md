# Apache Spark Sales Report Using PySpark

## Project Overview
This project demonstrates the use of Apache PySpark to process and analyze sales data. It loads a CSV dataset, performs data transformations, calculates regional sales summaries, and saves the final results in Parquet format.

## Technologies Used
- Python
- Apache PySpark
- Google Colab
- Pandas
- CSV
- Parquet

## Dataset Columns
- transaction_id
- customer_id
- product
- amount
- region

## Operations Performed
1. Initialized SparkSession.
2. Loaded CSV data into a Spark DataFrame.
3. Applied filter transformations.
4. Used count() to execute Spark operations.
5. Aggregated sales using groupBy().
6. Calculated total sales, transaction count, and average sales per region.
7. Exported the final results into Parquet format.

## Key Spark Concepts
- SparkSession
- DataFrames
- Lazy Evaluation
- Transformations
- Actions
- Distributed Processing
- Parquet Storage

## Project Output
Generated a regional sales report containing total sales, number of transactions, and average sales for each region.

## How to Run
1. Open the notebook using Google Colab.
2. Install PySpark.
3. Run all cells sequentially.
4. View the aggregated results and generated Parquet files.

## Author
Poornima
