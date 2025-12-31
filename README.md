# World Layoffs Data Cleaning & EDA (SQL)

## Project Overview
This project focuses on cleaning and exploring a global layoffs dataset
to prepare it for analysis and uncover key trends.

## The workflow follows a real-world data pipeline:
Raw Data → Cleaning → Exploratory Data Analysis (EDA).

## Tools Used
- MySQL
- MySQL Workbench


  ## Data Cleaning Steps
The following steps were performed using SQL:
1. Created a staging table to preserve the raw dataset
2. Removed duplicate records using ROW_NUMBER()
3. Standardized company names and text fields
4. Converted blank values to NULL
5. Validated schema and record counts


## The full cleaning logic can be found in:
<a href = "https://github.com/charles-tabi-gyansah/world_layoffs_data_cleaning_and_EDA/blob/main/Layoffs_Data%20Cleaning.sql">Data Cleaning</a>


## Exploratory Data Analysis (EDA)
EDA was conducted to understand:
- Layoffs trends over time
- Most affected countries and industries
- Companies with the highest layoffs

## Key queries are documented in:
  <a href = "https://github.com/charles-tabi-gyansah/world_layoffs_data_cleaning_and_EDA/blob/main/EDA_of_layoffs.sql"> EDA</a>


## Data cleaning logic
<img width="677" height="236" alt="Data_cleaning_logic" src="https://github.com/user-attachments/assets/3420d7d4-c1a9-4771-9132-30d84b2b8141" />


## Table schema
<img width="592" height="232" alt="Table Schema" src="https://github.com/user-attachments/assets/89fb1fb8-a95a-4b30-9e34-024a47742c1c" />


## EDA query
<img width="572" height="173" alt="EDA_query_screenshot" src="https://github.com/user-attachments/assets/aede1f0e-3ca6-4ae4-8e2d-deca981863a0" />


## Outcome
- Cleaned, analysis-ready dataset
- Removed duplicate and inconsistent records
- Generated insights into global layoff trends
  











   
