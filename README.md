# 🚢 Titanic Data Cleaning & Preprocessing

## 📌 Problem Statement

The goal of this project is to clean and preprocess the Titanic dataset so it becomes suitable for analysis and machine learning tasks.

---

## 📊 Dataset Information

* Dataset: Titanic Dataset
* Source: Kaggle
* Description: Contains passenger details such as age, gender, ticket class, fare, and survival status.

---

## 🛠️ Steps Performed

### 1. Data Loading & Understanding

* Loaded dataset using Pandas
* Checked structure using `.head()` and `.info()`

### 2. Handling Missing Values

* Filled missing values in **Age** using median
* Filled missing values in **Embarked** using mode
* Dropped **Cabin** column due to too many missing values

### 3. Data Cleaning

* Removed duplicate records
* Renamed columns for better readability

### 4. Feature Engineering

* Converted **Sex** column into numeric (0 = Male, 1 = Female)
* Applied One-Hot Encoding on **Embarked**

### 5. Final Output

* Clean dataset ready for analysis
* Saved as `clean_titanic.csv`

---

## 📈 Key Insights

* Data preprocessing is essential before analysis or modeling
* Handling missing values improves data quality
* Encoding categorical variables is required for machine learning

---

## 📁 Files in Repository

* `titanic (Data Cleaning).ipynb` → Main notebook
* `clean_titanic.csv` → Cleaned dataset
* `titanic.csv` → Original dataset
* `README.md` → Project documentation

---

## 🚀 Tools & Technologies

* Python
* Pandas
* NumPy
* Jupyter Notebook

---

## 🎯 Conclusion

This project demonstrates the importance of data cleaning in the data science pipeline. A well-prepared dataset leads to better analysis and model performance.

---

## 👤 Author

**Pushpesh Pant**
