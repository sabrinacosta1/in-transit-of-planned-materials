# In transit of planned materials
# Inventory and Material Analysis Automation

## Project Overview

This Python project automates the process of importing, cleaning, and analyzing inventory and material data from multiple Excel files. It leverages libraries such as **Pandas** and **NumPy** to handle large datasets, standardize information, and produce valuable insights into inventory levels, transit quantities, and material costs. The final output provides comprehensive reports to support inventory management decisions.

By showcasing advanced data manipulation and analysis skills, this project demonstrates proficiency in **data engineering**, **business intelligence**, and **Python automation**.

## Features

- **Data Import**: Reads and validates data from multiple Excel files, ensuring critical columns exist.
- **Data Normalization**: Standardizes material codes (ensuring 11-digit formatting) and other fields for consistency across datasets.
- **Automated Calculations**:
  - Aggregates inventory levels and quantities in transit.
  - Computes the total value of materials in transit.
  - Calculates unit prices and replaces missing values with default rules.
- **Business Insights**:
  - Identifies materials with discrepancies in stock levels.
  - Groups and reports material costs and transit values by month.
- **Export to Excel**: Outputs cleaned and enriched datasets into Excel files for further use.

## Key Functions
1. normalize_material(df, column_name)
Standardizes material codes by:

- Converting to uppercase.
- Stripping unnecessary spaces.
- Padding with zeros to ensure 11 digits.

2. Aggregations and Calculations
- Calculates stock levels, transit quantities, and total material costs.
- Groups insights by material and month.

3. Data Merging
- Combines data from multiple sources, such as Vorplan, SP99, and LX02, to ensure a unified dataset.

## Outputs
- Cleaned and Enriched Data: Normalized datasets with added columns for unit price, cumulative quantities, and transit values.
- Insights Report: Monthly report of the total material value in transit, outputted as an Excel file.

## Why This Project Stands Out
Real-World Application: Demonstrates an end-to-end data pipeline for inventory analysis.
Advanced Data Handling: Uses aggregation, merging, and conditional logic to clean and analyze data.
Automation: Saves time by eliminating manual data processing.
Impact-Driven Insights: Translates raw data into actionable business metrics.
