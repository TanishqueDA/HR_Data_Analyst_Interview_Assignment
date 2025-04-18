# 📊 HR Analytics Project

## 🚀 Overview

This project performs exploratory data analysis (EDA), visualization, and statistical modeling on an HR dataset to uncover insights related to performance, compensation, tenure, and attrition.

---

## 🧰 Tools & Libraries

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![pandas](https://img.shields.io/badge/pandas-1.5+-lightgrey?logo=pandas)
![seaborn](https://img.shields.io/badge/seaborn-0.11+-lightblue?logo=seaborn)
![matplotlib](https://img.shields.io/badge/matplotlib-3.6+-orange?logo=matplotlib)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-yellow?logo=scikit-learn)

---

## 📁 Dataset Features

| Column Name                | Description                                |
|---------------------------|--------------------------------------------|
| Employee Number           | Unique ID for each employee                |
| Gender                    | Male/Female                                |
| Date Of Joining           | Date employee joined                       |
| Leaving Date              | Null if active, else date of exit          |
| Department                | Department assigned                        |
| Annual Performance Rating | Scale of 1 to 5                            |
| ANNUAL CTC                | Annual cost to company (salary)            |

---

## 📌 Key Analyses

<details>
<summary>🧹 Data Cleaning</summary>

- Converted dates to datetime
- Standardized column names
- Filled missing values in `Leaving Date` for active employees
- Calculated `Tenure` and `Currently Working` columns

</details>

<details>
<summary>📊 Exploratory Data Analysis</summary>

- Gender and department distribution
- Performance rating trends
- Tenure histograms and turnover analysis
- Salary vs performance and tenure

</details>

<details>
<summary>📈 Visualizations</summary>

- Bar plots for department and gender split
- Box plots for salary and performance across departments
- Correlation matrix heatmap for numeric features

</details>

<details>
<summary>📉 Statistical Modeling</summary>

- Feature engineering with `get_dummies()`
- Linear regression to predict Annual CTC
- Model evaluation using MAE, MSE, R²

</details>

---

## 📌 Sample Insights

- **Average tenure of leavers:** *X years*
- **Departments with highest turnover:** *Y*
- **Correlation between performance and salary:** *0.42*
- **Average annual CTC:** ₹*Z lakhs*

---

## 💡 Future Enhancements

- Add Streamlit dashboard
- Predict attrition using classification models
- Export reports to Google Sheets for real-time visibility

---

