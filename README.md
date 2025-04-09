# Azure Synapse Spark ETL Notebook

This repository contains a Spark notebook used in Azure Synapse Studio to perform data transformation tasks using Apache Spark.

## 🔧 Technologies Used
- Azure Synapse Analytics
- Apache Spark (via Spark Pools)
- Azure Data Lake Storage Gen2
- Synapse Studio

## 📁 Contents
- `spark_transform.ipynb`: Spark notebook used to load and transform sales data

## 🚀 How to Use
1. Open Synapse Studio from your Synapse Workspace.
2. Go to the Develop section and import the `spark_transform.ipynb` file.
3. Attach the notebook to your Spark pool (e.g., `sparkXXXXXX`).
4. Run all code cells in order (the first cell may take longer to start the Spark session).

## 🧹 Clean Up
To avoid unnecessary charges, delete the resource group (`dp203-xxxxxxx`) from the Azure portal after completing the exercise.

