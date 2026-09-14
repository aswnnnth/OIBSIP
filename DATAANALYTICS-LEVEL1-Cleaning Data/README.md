# DATA ANALYTICS – LEVEL 1 – DATA CLEANING

## 📌 Project Overview

This project was completed as part of the **Oasis Infobyte Data Analytics Internship (OIBSIP)**.

The project focuses on applying professional **data cleaning and preprocessing techniques** to improve data quality and prepare the dataset for further analysis.

## 🎯 Objective

The objective of this project is to demonstrate practical data cleaning techniques by:

- Identifying and handling missing values
- Detecting and removing duplicate records
- Checking and correcting data types
- Identifying and handling outliers
- Comparing data quality before and after cleaning
- Preparing a clean dataset for future analysis

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook

## 🔍 Data Cleaning Process

### 1. Data Loading & Inspection

The dataset was loaded and inspected to understand its structure, columns, data types, and overall data quality.

### 2. Data Quality Report

A data quality report was generated to identify potential issues such as:

- Missing values
- Duplicate records
- Incorrect data types
- Potential outliers

### 3. Handling Missing Values

Missing values were identified and handled appropriately.

For numerical columns, missing values were filled using the **median**, which helps reduce the influence of extreme values.

The `Cabin` column was removed because it contained an excessive number of missing values.

### 4. Duplicate Records

The dataset was checked for duplicate records to ensure that repeated entries did not affect the analysis.

### 5. Data Type Verification

The data types of the columns were checked and verified to ensure that the data was in the appropriate format for analysis.

### 6. Outlier Detection

Outliers were identified using the **Interquartile Range (IQR)** method.

The IQR method was used to determine values that fall outside the expected range.

### 7. Before vs. After Data Quality

A comparison of the dataset before and after cleaning was performed to evaluate the improvements in data quality.

### 8. Cleaned Dataset

After completing the cleaning process, the cleaned dataset was exported for use in future analysis.

## 📊 Project Highlights

- Loaded and inspected the dataset.
- Generated a data quality report.
- Identified missing values.
- Filled missing numerical values using the median.
- Removed the `Cabin` column due to excessive missing values.
- Checked for duplicate records.
- Verified data types.
- Detected outliers using the IQR method.
- Compared data quality before and after cleaning.
- Exported the cleaned dataset for future analysis.

## 📁 Project Files

- `Data_Cleaning.ipynb` – Jupyter Notebook containing the complete data cleaning process.
- `Data_Cleaning.html` – HTML version of the completed notebook.
- `data/` – Dataset used for the project and/or information about the dataset.

## 📈 Outcome

The dataset was successfully cleaned and prepared for further analysis by addressing missing values, duplicate records, data types, and outliers.

This project demonstrates the importance of **data quality and preprocessing** as a fundamental step in the data analytics workflow.

## 📌 Status

**Completed ✅**

## 👤 Author

**Aswanth K**

Data Analytics Intern – OIBSIP
