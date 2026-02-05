<h1 align="center">✨ Data Immersion & Wrangling Project ✨</h1>

<p align="center">
Transforming raw customer data into clean, reliable, and analysis-ready insights using Python & Pandas.
</p>

---

## 🌸 About This Project

Real-world data is rarely perfect.  
In this project, I worked on understanding and cleaning a customer sales dataset by identifying data quality issues and transforming the data into a usable format.

This project helped me learn how data preprocessing plays a major role before performing any analysis or machine learning.

---

## 🎯 Project Goals

✔ Understand dataset structure  
✔ Identify data quality problems  
✔ Clean and preprocess the dataset  
✔ Create meaningful new features  
✔ Prepare dataset for analysis  

---

## 📊 Dataset Overview

The dataset contains customer purchase and demographic details.

| Column | Description |
|----------|-------------|
| 🆔 Customer_ID | Unique customer number |
| 👤 Name | Customer name |
| 🎂 Date_of_Birth | Customer birth date |
| 🛍 Purchase_Date | Date of purchase |
| 💰 Purchase_Amount | Amount spent |
| 🌍 City | Customer location |
| ⚧ Gender | Customer gender |

---

## ⚠️ Challenges Found in Dataset

While exploring the data, I found:

🔹 Missing city values  
🔹 Missing purchase amounts  
🔹 Duplicate records  
🔹 Inconsistent gender formatting  
🔹 Extreme purchase values (Outliers)  

---

## 🛠 Steps Performed

### 🔍 Data Familiarization
Explored dataset using Pandas functions to understand structure and quality.

---

### 📚 Data Dictionary Creation
Documented column meanings and business importance.

---

### 🧹 Data Cleaning

✔ Removed duplicate records  
✔ Filled missing city values with **"Unknown"**  
✔ Replaced missing purchase values with **average amount**  
✔ Standardized gender formatting  

---

### 🔄 Data Transformation
Converted date columns into datetime format for better analysis.

---

### 🧠 Feature Engineering
Created a new column:

✨ **Customer Age** (Derived from Date of Birth)

---

### 📉 Outlier Removal
Used Interquartile Range (IQR) statistical method to remove abnormal purchase values.

---

## 📁 Project Structure

