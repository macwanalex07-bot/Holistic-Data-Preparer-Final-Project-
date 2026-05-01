# 📊 Holistic Data Preparer – Customer Credit Risk Analysis

## 🚀 Project Overview

This project demonstrates a **complete end-to-end data preprocessing and feature engineering pipeline** for a Customer Credit Risk dataset.

The goal is to transform raw, multi-source data into a **clean, structured, and machine learning–ready dataset** suitable for predicting loan default risk.

---

## 🎯 Objectives

* Perform **data acquisition** from multiple sources (CSV, JSON, SQL, API)
* Apply **data cleaning and preprocessing techniques**
* Handle **missing values and outliers**
* Perform **feature engineering and transformation**
* Apply **encoding and scaling techniques**
* Generate a **high-quality dataset ready for ML modeling**

---

## 📂 Project Structure

```
project/
│── data/
│   ├── customers.csv
│   ├── customers.json
│   ├── customers.db
│
│── notebook/
│   └── preprocessing.ipynb
│
│── output/
│   └── final_cleaned_dataset.csv
│
│── report/
│   └── report.pdf
│
│── README.md
```

---

## 🧩 Data Sources

The dataset was collected and integrated from:

* 📄 CSV file (main dataset)
* 📦 JSON file (customer metadata)
* 🗄️ SQL database (structured records)
* 🌐 API (external simulated data)

---

## ⚙️ Technologies Used

* **Python**
* **Pandas & NumPy**
* **Scikit-learn**
* **SciPy**
* **ydata-profiling**
* **Matplotlib**

---

## 🔍 Data Preprocessing Steps

### ✔ Data Understanding

* `.info()` and `.describe()`
* Pandas Profiling report generation

### ✔ Missing Value Handling

* Mean / Median Imputation
* Most Frequent Imputation
* KNN Imputer
* MICE (Iterative Imputer)
* Random Sampling + Indicator
* Complete Case Analysis

### ✔ Outlier Handling

* Z-score Method
* IQR Method
* Percentile Method
* Winsorization

### ✔ Feature Engineering

* Date feature extraction (Year, Month, Day, Weekday)
* Debt-to-Income Ratio
* Average Monthly Transactions
* Spending-to-Income Ratio

### ✔ Encoding

* Ordinal Encoding (education level)
* Label Encoding (binary features)
* One-Hot Encoding (categorical variables)

### ✔ Feature Transformation

* Log Transformation
* Square Root Transformation
* Power Transformation (Yeo-Johnson)

### ✔ Feature Scaling

* StandardScaler
* MinMaxScaler
* RobustScaler
* MaxAbsScaler
* Normalization

---

## 📊 Key Insights

* Advanced imputation methods (KNN, MICE) improved data quality significantly
* Winsorization effectively handled outliers without data loss
* Feature engineering enhanced predictive capability
* RobustScaler performed best due to presence of outliers
* Financial behavior features (e.g., debt-to-income) are strong predictors of default

---

## 📦 Final Output

* ✅ Cleaned and transformed dataset
* 📁 `final_cleaned_dataset.csv`
* Ready for machine learning modeling

---

## 🧠 Machine Learning Readiness

The dataset is:

* ✔ Clean (no missing values)
* ✔ Consistent
* ✔ Properly encoded
* ✔ Scaled and normalized
* ✔ Feature-rich

👉 Suitable for:

* Logistic Regression
* Decision Trees
* Random Forest
* Gradient Boosting

---

## 📌 How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/credit-risk-project.git
```

2. Install dependencies:

```
pip install pandas numpy scikit-learn scipy ydata-profiling matplotlib
```

3. Run the notebook:

```
jupyter notebook
```

---

## 📄 Deliverables

* ✔ Jupyter Notebook
* ✔ Final Dataset
* ✔ Project Report (PDF)
* ✔ README Documentation

---

## 🏁 Conclusion

This project successfully demonstrates a **complete data preprocessing pipeline**, transforming raw and unstructured data into a **high-quality, machine learning-ready dataset**.

---

## 👨‍💻 Author

**Your Name**
Macwan Alex
(Data Science Student)

---

## ⭐ Acknowledgment

This project was developed as part of a **Data Preprocessing & Feature Engineering final project**.

---
