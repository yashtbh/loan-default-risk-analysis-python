# Loan Default Risk Analysis using Python

This project performs Exploratory Data Analysis (EDA) on the **application_data.csv** dataset from the [Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk) Kaggle competition. The goal is to identify the key factors that influence loan default risks.

---

## 🧠 Objective

To analyze demographic and financial information of loan applicants and uncover patterns associated with loan default risk, using Python-based data analysis.

---

## 📌 Dataset

- **File used:** `application_data.csv`
- Contains customer demographics, income, credit amount, employment, and loan status.
- `TARGET` column indicates loan status (1 = default, 0 = repaid)

---

## 🧰 Tools & Libraries

- Python 3
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn

---

## 📊 Key Analysis Performed

### ✅ Data Cleaning
- Removed redundant columns
- Handled missing values with median/mode
- Capped outliers using the IQR method

### ✅ Univariate & Bivariate Analysis
- Age distribution, income levels, credit amounts
- Gender vs. default rate
- Occupation & education impact on loan default

### ✅ Correlation Analysis
- AMT_CREDIT vs. AMT_GOODS_PRICE and AMT_ANNUITY
- DAYS_BIRTH vs. DAYS_EMPLOYED

---

## 🔍 Key Insights

- **Younger individuals (27–35)** are more likely to default
- **Higher income** = lower risk
- **Manual labor jobs** are riskier than white-collar jobs
- **Education level** inversely correlates with default rate

---



