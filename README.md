<p align="center">
  <!-- Main Tech Badges -->
  <img src="https://img.shields.io/badge/Python-3.9-blue.svg" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange.svg" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen.svg" />
  <img src="https://img.shields.io/badge/Category-Machine%20Learning-purple.svg" />
  <img src="https://img.shields.io/badge/Dataset-IBM%20HR%20Analytics-red.svg" />

  <!-- Models -->
  <br><br>
  <img src="https://img.shields.io/badge/Simple%20Regression-Model-blue.svg" />
  <img src="https://img.shields.io/badge/Multiple%20Regression-Model-purple.svg" />
</p>

## HR-Salary-Prediction
Predicting Monthly Income using Simple & Multiple Linear Regression on the IBM HR Analytics Dataset.

 ## HR Salary Prediction – Regression Analysis
This project examines key factors influencing Monthly Income using both Simple and Multiple Linear Regression models.
The analysis includes full statistical diagnostics, assumption validation, model comparison, and cross-validation to ensure rigorous and reliable results.

---

## 📂 Project Structure
HR-Salary-Prediction/
│
├── Code/
│    ├── Simple_regression.ipynb
│    ├── Multiple_regression.ipynb
│
├── Data/
│    └── WA_Fn-UseC_-HR-Employee-Attrition.csv
│
├── Report/
│    └── Final_Project_ReportSMDA.docx
│
├── requirements.txt
├── LICENSE
├── README.md
└── .gitignore


---

##  Models Implemented
-Simple Linear Regression (JobLevel → MonthlyIncome)
-Multiple Linear Regression (JobLevel + TotalWorkingYears + Age + YearsAtCompany)

---

##  Key Findings
-Job Level explains most variance in Monthly Income (R² = 0.891).
-Multiple Regression improves R² slightly to 0.895 (+0.003).
-The simple model is preferred due to higher interpretability and minimal loss in accuracy.

---

##  Techniques Used
- Outlier detection (Z-score, IQR)
- Correlation heatmap
- Residual diagnostics
- Cross-validation (5-fold)
- Multicollinearity (VIF)
- Model comparison: R², RMSE, MAE, AIC, BIC

---

##  Dataset
IBM HR Analytics Employee Attrition & Performance Dataset (Public)

---

## Prepared by
**Maram**  
Master’s Student – Data Science  
Course: 6212CDS – Statistical Methods for Data Analysis

---

##  License
MIT License
