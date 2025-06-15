# Spark Transformation with PySpark in Jupyter Notebook

## 📘 Overview

This project demonstrates a basic Spark data transformation workflow using PySpark in a Jupyter Notebook environment. The project connects to a Spark cluster, performs data manipulation using Spark DataFrames, and writes the output to a Parquet file.

## 🚀 Features

- Connect to remote/local Spark cluster
- Use SparkSession and Spark DataFrames
- Perform filtering, aggregation, and column transformations
- Save results in efficient Parquet format

## 🧱 Project Structure

basic-spark-transformation/
├── transformation.ipynb # Main transformation notebook
├── README.md # Project documentation
├── .gitignore # Ignore local settings, checkpoints, etc.
└── data/ # Input/output 


## ⚙️ Requirements

- Python 3.7+
- Apache Spark 3.x
- PySpark
- Jupyter Notebook or JupyterLab

Install dependencies:

```bash
pip install pyspark
