## HR-Salary-Prediction
Predicting Monthly Income using Simple & Multiple Linear Regression on the IBM HR Analytics Dataset.

 ## HR Salary Prediction – Regression Analysis
This project examines key factors influencing Monthly Income using both Simple and Multiple Linear Regression models.
The analysis includes full statistical diagnostics, assumption validation, model comparison, and cross-validation to ensure rigorous and reliable results.

---

## 📂 Project Structure
HR-Salary-Prediction/
│
├── 📁 Report/
│    └── HR_Salary_Prediction_Report.pdf
│
├── 📁 Code/
│    ├── simple_regression.ipynb
│    ├── multiple_regression.ipynb
│
├── 📁 Data/
│    └── HR_data.csv     # Public dataset
│
└── README.md


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
