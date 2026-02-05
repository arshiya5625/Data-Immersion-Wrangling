# Data Immersion and Wrangling Project

## Project Overview
This project focuses on understanding, cleaning, and preparing a customer sales dataset for analysis. The main goal is to identify data quality issues and transform raw data into a structured and reliable dataset using Python and Pandas.

---

## Project Objective
The objective of this project is to perform data preprocessing by:

- Understanding the dataset structure  
- Creating a data dictionary  
- Identifying data quality issues  
- Cleaning and transforming data  
- Performing feature engineering  
- Removing outliers  
- Preparing the final dataset for analysis  

---

## Dataset Description

The dataset contains customer demographic and purchase information.

| Column Name | Description |
|-------------|-------------|
| Customer_ID | Unique customer identifier |
| Name | Customer name |
| Date_of_Birth | Customer birth date |
| Purchase_Date | Date of purchase |
| Purchase_Amount | Amount spent by customer |
| City | Customer location |
| Gender | Customer gender |

---

## Data Quality Issues Identified

During data profiling, the following issues were found:

- Missing values in City and Purchase Amount  
- Duplicate customer records  
- Inconsistent Gender formatting  
- Outliers in Purchase Amount  
- Date format inconsistencies  

---

## Data Cleaning and Transformation Steps

### Duplicate Removal
Duplicate rows were removed to maintain data accuracy and uniqueness.

### Missing Value Handling
- Missing City values were replaced with "Unknown"  
- Missing Purchase Amount values were replaced using mean value  

### Categorical Data Standardization
Gender column values were standardized to maintain consistency.

### Date Conversion
Date_of_Birth and Purchase_Date columns were converted into datetime format.

### Feature Engineering
A new column "Customer_Age" was created usin_
