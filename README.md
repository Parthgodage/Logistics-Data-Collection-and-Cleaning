
# Logistics Data Collection and Cleaning Strategies

## Project Overview

This project focuses on data collection, exploration, cleaning, and validation techniques in the logistics domain using Python.

The project uses the Brazilian E-Commerce Public Dataset by Olist to understand logistics data quality issues and prepare an analysis-ready dataset.

## Objectives

- Understand logistics data collection strategies.
- Import and explore public logistics datasets.
- Identify missing values and duplicate records.
- Convert date columns into proper datetime formats.
- Detect invalid date sequences.
- Create a cleaned and validated dataset.
- Visualize logistics data using Python.

## Dataset Description

Dataset: Brazilian E-Commerce Public Dataset by Olist

Main File: olist_orders_dataset.csv

Original Dataset:
- Total Records: 99,441
- Total Columns: 8

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- GitHub

## Methodology

1. Dataset Collection
2. Data Import
3. Data Exploration
4. Missing Values Analysis
5. Duplicate Detection
6. Date Format Conversion
7. Invalid Date Validation
8. Data Cleaning
9. Data Visualization
10. CSV Export

## Key Findings

- Total Orders: 99,441
- Original Columns: 8
- Duplicate Rows: 0
- Duplicate Order IDs: 0
- Missing Values: 4,908
- Invalid Date Sequences: 23

Missing values were preserved with indicators instead of being filled with arbitrary values.

Invalid date sequences were flagged for further investigation without deleting original records.

## Project Files

- Logistics_Data_Cleaning_Project.ipynb
- Logistics_Cleaned_Dataset.csv
- missing_values_analysis.png

## Conclusion

This project demonstrates the importance of data quality in logistics operations.

Using Python, missing values, duplicate records, and invalid date sequences were identified and investigated. Date formats were standardized, and a validated dataset was exported for further analysis.

The project helped develop practical skills in data collection, data preprocessing, data validation, and visualization.

## Dataset Source

Kaggle - Brazilian E-Commerce Public Dataset by Olist.
