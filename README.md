# Data-Immersion-Wrangling
Customer dataset cleaning and preprocessing using Python and Pandas.
# Data Immersion & Wrangling Project

## About This Project

In this project, I worked on cleaning and preparing a customer sales dataset. The main aim was to understand how real-world data looks and how it can be converted into a clean and usable format for analysis.

During this project, I learned that real datasets often contain errors, missing values, duplicates, and inconsistent information. This project helped me understand how to handle those issues using Python and Pandas.

---

## Project Objective

The goal of this project was to:

• Understand the dataset  
• Identify data quality problems  
• Clean and transform the data  
• Create useful new features  
• Prepare the dataset for further analysis  

---

## Dataset Information

The dataset contains customer details and purchase information.

### Columns Included:
- Customer ID
- Customer Name
- Date of Birth
- Purchase Date
- Purchase Amount
- City
- Gender

---

## Problems Found in Dataset

While analyzing the dataset, I found several issues:

• Some city values were missing  
• Purchase amount had missing entries  
• Duplicate customer records were present  
• Gender column had inconsistent formatting  
• Some purchase values were extremely high or low  

---

## Steps I Performed

### 1. Data Understanding
I first loaded the dataset and explored its structure using Pandas functions like head(), info(), and describe().

---

### 2. Data Dictionary
I created a data dictionary explaining each column, its data type, and its business importance.

---

### 3. Data Cleaning

I performed the following cleaning steps:

• Removed duplicate records  
• Filled missing city values with "Unknown"  
• Replaced missing purchase amounts with average values  
• Standardized gender column formatting  

---

### 4. Data Transformation
I converted date columns into datetime format to make them easier to analyze.

---

### 5. Feature Engineering
I created a new column called Customer Age using the Date of Birth column.

---

### 6. Outlier Removal
I removed extreme purchase values using the IQR statistical method.

---

## Final Result

After completing all preprocessing steps, I generated a cleaned dataset that is ready for analysis and machine learning tasks.

---

## Tools Used

Python  
Pandas  
NumPy  
Jupyter Notebook  

---

## What I Learned

This project helped me understand:

• Importance of data cleaning  
• Handling missing values and duplicates  
• Feature engineering techniques  
• Statistical methods for outlier detection  
• Real-world data preprocessing workflow  

---

## Project Files

customer_sales_dataset.csv – Raw dataset  
cleaned_customer_sales.csv – Cleaned dataset  
data_dictionary.csv – Column description  
data_cleaning.ipynb – Complete implementation  

---

## Author

Arshiya Ruksar

---

This project was completed as part of my learning and internship experience in data preprocessing and analysis.
