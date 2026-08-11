# Pandas Data Input, Missing Value Handling and File Processing

## Overview

This project demonstrates how **Pandas** can be used to read data from different sources, handle missing values, display datasets, and save processed data into new files.

The implementation works with data from **CSV files, Excel files, and an online CSV dataset**. It demonstrates practical data preprocessing techniques that are commonly used in Data Analysis and Visualization.

## Objectives

* Read data from CSV files.
* Read data from Excel files.
* Read data from an online CSV source.
* Display and inspect imported datasets.
* Handle missing values using different techniques.
* Remove rows containing missing values.
* Save processed data into CSV files.
* Save processed data into Excel files.
* Understand basic data preprocessing using Pandas.

## Data Sources

The program works with three different data sources:

### 1. CSV File

A local CSV file containing Android application information is loaded and processed.

### 2. Excel File

An Excel file containing product-related information is loaded from a specified worksheet.

### 3. Web-Based CSV File

A CSV dataset is retrieved from an online GitHub repository. The dataset contains information about countries and their respective regions.

## Concepts Covered

### 1. Reading CSV Files

Pandas is used to import structured data stored in CSV format into a DataFrame.

### 2. Reading Excel Files

The program demonstrates how to read data from an Excel workbook and access a specific worksheet.

### 3. Reading Data from the Web

Pandas can directly retrieve CSV data from a publicly accessible URL and convert it into a DataFrame.

### 4. Displaying Data

The first few records of each dataset are displayed to verify that the data has been successfully loaded.

### 5. Handling Missing Values

Different techniques are demonstrated for handling missing values:

* **Forward filling:** Missing values are replaced using the previous available value.
* **Backward filling:** Missing values are replaced using the next available value.
* **Dropping missing values:** Rows containing missing values are removed.

These techniques help improve data quality before further analysis.

### 6. Saving Processed Data

After preprocessing, the datasets are exported into new files.

The project demonstrates saving data as:

* CSV
* Excel

## Files Used

```text
Pandas-Data-Input/
│
├── Google_data (2b.c1).csv
├── data (2c2).xlsx
├── program.ipynb
└── README.md
```

## Generated Files

After execution, the processed datasets can be saved as:

```text
processed_text.csv
processed_excel.xlsx
```

## Requirements

* Python 3.x
* Pandas
* Jupyter Notebook or JupyterLab
* OpenPyXL for Excel file operations
* Internet connection for accessing the online dataset

## Installation

Install the required packages using:

```bash
pip install pandas openpyxl jupyter
```

## Applications

The concepts demonstrated in this project are useful for:

* Data preprocessing
* Data cleaning
* Data integration
* CSV file processing
* Excel file processing
* Web-based data collection
* Handling missing values
* Dataset preparation
* Exploratory Data Analysis (EDA)
* Data Science and Machine Learning workflows

## Note

The dataset URL used in the program should be publicly accessible. If the online dataset location changes, the URL can be replaced with another valid CSV data source.

The program may also display a warning when using older Pandas syntax for missing-value handling. Modern Pandas versions recommend using `ffill()` and `bfill()` directly instead of the deprecated `fillna(method=...)` approach.

## Conclusion

This project demonstrates the basic techniques required to **import, inspect, preprocess, and export data using Pandas**. By working with CSV files, Excel files, and online datasets, the implementation provides practical experience in handling data from multiple sources and preparing it for further analysis.

## Author

**Vishnu A**

**Course:** Computer Science and Engineering
**Subject:** Data Analysis and Visualization (DAV)
