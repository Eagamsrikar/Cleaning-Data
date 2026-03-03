# Data Cleaning Project

## 📌 Project Overview

This project focuses on **Data Cleaning**, an essential step in the data analysis process. The goal is to identify and correct inaccurate, incomplete, duplicate, or inconsistent data to ensure high data quality and reliable analytical results.

Clean and well-structured data improves decision-making, enhances model performance, and ensures accurate insights. This project demonstrates practical data cleaning techniques using Python.

---

## 🎯 Objectives

* Ensure data integrity and consistency.
* Handle missing and incomplete data.
* Identify and remove duplicate records.
* Standardize data formats for consistency.
* Detect and handle outliers that may affect analysis.
* Prepare a clean dataset ready for analysis or machine learning.

---

## 📂 Dataset Description

The dataset contains Airbnb listing information, including:

* **id** – Listing identifier
* **name** – Listing name
* **host_name** – Host name
* **neighbourhood_group** – Area group
* **room_type** – Type of room offered
* **price** – Listing price
* **minimum_nights** – Minimum stay requirement
* **number_of_reviews** – Total reviews
* **reviews_per_month** – Monthly review rate
* **availability_365** – Availability days in a year

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and cleaning
* **NumPy** – Numerical operations
* **Matplotlib** – Visualization
* **Seaborn** – Statistical visualization

---

## ⚙️ Project Workflow

### 1️⃣ Data Loading

* Imported dataset using Pandas.
* Examined dataset structure and data types.

### 2️⃣ Data Integrity Check

* Verified column names and formats.
* Checked dataset size and consistency.

### 3️⃣ Missing Data Handling

* Identified missing values.
* Replaced missing text values with `"Unknown"`.
* Filled numerical missing values using median imputation.

### 4️⃣ Duplicate Removal

* Detected duplicate records.
* Removed duplicates to maintain uniqueness.

### 5️⃣ Data Standardization

* Converted text columns to consistent lowercase format.
* Removed extra spaces and formatting inconsistencies.

### 6️⃣ Outlier Detection

* Used **Interquartile Range (IQR)** method.
* Detected extreme price values.
* Removed outliers to improve data reliability.

### 7️⃣ Data Validation & Export

* Verified cleaned dataset statistics.
* Exported cleaned dataset as a new CSV file.

---

## 📊 Key Outcomes

* Improved data accuracy and consistency.
* Reduced noise caused by missing values and outliers.
* Created a reliable dataset suitable for further analysis.
* Demonstrated practical data preprocessing skills.

---

## 🚀 How to Run the Project

### Step 1: Install Required Libraries

```
pip install pandas numpy matplotlib seaborn
```

### Step 2: Add Dataset

Place the dataset file:

```
AB_NYC_2019.csv
```

in the project folder.

### Step 3: Run the Script

```
python data_cleaning.py
```

---

## 📈 Output

The project generates:

* Cleaned dataset (`cleaned_airbnb_data.csv`)
* Data quality checks
* Outlier visualization plots
* Statistical summaries

---

## ✅ Skills Demonstrated

* Data preprocessing
* Missing value treatment
* Duplicate detection
* Data standardization
* Outlier analysis
* Data validation

---

## 🔮 Future Enhancements

* Automated data cleaning pipeline.
* Advanced anomaly detection techniques.
* Integration with machine learning workflows.
* Interactive data quality dashboards.
