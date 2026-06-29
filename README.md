# 🏠 New York City Airbnb Open Data Cleaning

## 📌 Project Overview

This project focuses on cleaning the New York City Airbnb Open Data dataset using Python and Pandas. Data cleaning is an essential step in data analytics because raw datasets often contain missing values, incorrect data types, duplicate records, and outliers.

The cleaned dataset is prepared for further Exploratory Data Analysis (EDA), visualization, and machine learning applications.

---

## 📂 Dataset

Dataset: New York City Airbnb Open Data (2019)

The dataset contains information about Airbnb listings in New York City, including:

- Listing details
- Host information
- Room types
- Prices
- Reviews
- Availability
- Neighborhoods

Total Records: **48,895**

Total Features: **16**

---

## 🛠️ Data Cleaning Performed

✔ Checked dataset structure

✔ Checked missing values

✔ Filled missing values:
- host_name → Unknown
- reviews_per_month → 0
- last_review → Converted to datetime

✔ Checked duplicate records

✔ Verified data types

✔ Converted last_review to datetime format

✔ Detected outliers using Boxplot

✔ Removed outliers using IQR (Price column)

✔ Checked unique values

✔ Saved cleaned dataset

---

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

---

## 📈 Learning Outcomes

- Data Cleaning
- Missing Value Handling
- Datetime Conversion
- Duplicate Detection
- Outlier Detection
- Data Validation
- Dataset Preparation

---

## 📁 Output

- Cleaned Airbnb Dataset (`cleaned_airbnb.csv`)
