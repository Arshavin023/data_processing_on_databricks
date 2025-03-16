# Data Processing on DataBricks
## Overview
This repository contains a SparkSQL and PySpark codes for data processing on DataBricks

# Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Execution Flow](#execution-flow)


## Introduction <a name="introduction"></a>
This project leveraged Delta Live Tables (DLT) and Python (PySpark) to construct a robust data pipeline within a Jupyter Notebook. The workflow encompassed the ingestion of customer and loan_applications data from Azure Blob storage, creation of Delta Live Tables and processing of data at bronze, silver, and gold layers, configuration the DLT pipeline, and scheduling of the DLT pipeline for seamless automation.

## Prerequisites <a name="prerequisites"></a>
Before running this report generation process, the following prerequisite must be meant.

- datasets is stored in parquet format and mounted on Azure Blob Storage

## Installation <a name="installation"></a>

Clone the repository to your local machine:

``` 
git clone https://github.com/Arshavin023/data_processing_on_databricks.git
```

## Execution Flow
- Run codes in each cell of the Jupyter notebook sequentially