# Employee Attrition Analysis

This is one of my data analytics projects where i tried to figure out why employees leave a company and also predict who is likely to leave in future. Built this using Python in Google Colab and made a Power BI dashboard to show the insights visually.

---

## About the Project

Employee attrition is a big problem for companies. Hiring new people is costly and time consuming so its better to know in advance who might leave. In this project i did both things — analyzed the reasons behind attrition and also built a model to predict it.

Used Logistic Regression for prediction and Power BI to show everything in a clean dashboard.

---

## Dataset

- Source: IBM HR Analytics Employee Attrition Dataset (Kaggle)
- Total records: 1470 employees
- Target column: Attrition (Yes / No)
- Key features: Age, Department, Job Role, Monthly Income, Years at Company, Work Life Balance, Job Satisfaction, Overtime etc.

---

## Steps followed in the notebook

1. Imported all required libraries
2. Loaded the dataset
3. Did Exploratory Data Analysis to understand patterns
4. Cleaned the data and handled categorical columns
5. Visualized attrition by department, age, income and other factors
6. Separated features (X) and target (y)
7. Applied Label Encoding and Feature Scaling
8. Split into train and test sets
9. Trained Logistic Regression model
10. Evaluated model using accuracy, precision, recall and confusion matrix

---

## Key Findings

- Employees who do overtime are more likely to leave
- People with lower monthly income have higher attrition rate
- Sales department has the highest attrition compared to others
- Employees with less years at company tend to leave more

---

## Tools and Libraries used

- Python (Google Colab)
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Power BI (for dashboard)

---

## Folder structure

```
├── notebooks/        --> colab notebook
├── dashboard/        --> power bi dashboard file
└── README.md
```
## Open google collab file
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/uml-by-yash/Employee-attrition-analysis/blob/main/Notebook/Employee_attrition_analysis.ipynb)
---

Made by Yash Patel
B.E. IT — LDRP-ITR, KSV (2025-26)
