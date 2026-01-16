# elevatelabs-task-2-
This repo contains tasks from my internship "ElevateLabs"
# AI & ML Internship – Task 2  
## Data Cleaning & Missing Value Handling

## 📌 Objective
The objective of this task is to clean the dataset by identifying missing values, applying appropriate imputation techniques, removing columns with excessive missing data, and validating the dataset for machine learning readiness.

---

## 📊 Dataset Used
- **House Prices Dataset**

---

## 🛠 Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Jupyter Notebook / Google Colab  

---

## 🔍 Task Overview
The following steps were performed in this task:

- Loaded the dataset and analyzed its structure
- Identified missing values using `.isnull().sum()`
- Visualized missing value patterns using bar charts
- Applied median imputation for numerical features
- Applied mode imputation for categorical features
- Removed columns with extremely high missing values
- Validated the dataset after cleaning
- Compared dataset quality before and after cleaning
- Saved the cleaned dataset for further use

---

## 📈 Key Observations
- Several columns contained missing values
- Numerical columns were imputed using **median** to handle outliers
- Categorical columns were imputed using **mode**
- Columns with more than 40% missing values were removed
- After cleaning, no missing values remained in the dataset

---

## 🤖 Machine Learning Readiness
✔ Clean and structured dataset  
✔ No missing values  
✔ Reduced noise and improved data quality  
✔ Ready for regression modeling  

---

## 📁 Repository Structure
