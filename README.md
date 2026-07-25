# Probability of Default (PD) and Scorecard Development using WOE and Logistic Regression

## Overview

This project develops an end-to-end **Probability of Default (PD) Scorecard** using the traditional credit risk modelling methodology widely adopted by banks and financial institutions. The objective is to estimate the likelihood of customer default by leveraging demographic information, repayment history, billing behaviour, and payment patterns.

This scorecard follows a framework based on **Weight of Evidence (WOE)** transformation and **Logistic Regression**, enabling business-friendly risk assessment and customer risk ranking.

---

## Project Highlights

- Developed a traditional **Probability of Default (PD) Scorecard** using **Weight of Evidence (WOE)** and Logistic Regression.
- Performed comprehensive **Exploratory Data Analysis (EDA)**, fine classing, coarse classing, WOE transformation, and Information Value (IV) analysis.
- Selected variables using **IV analysis, multicollinearity assessment (VIF), and backward feature elimination**.
- Evaluated model performance using **ROC-AUC, KS Statistic, Lift Analysis, Confusion Matrix, Precision, Recall, and F1-Score**.
- Optimised the classification threshold using **Youden's Index** to improve default identification.
- Converted the final logistic regression model into a **production-style points-based credit scorecard** through score scaling.
- Demonstrated scorecard implementation by calculating the final credit score for an individual customer.

---

## Model Performance

| Metric | Value |
|---------|------:|
| ROC-AUC | **0.767** |
| KS Statistic | **39.7%** |
| Optimal Threshold | **0.224** |
| Precision | **48.3%** |
| Recall | **57.8%** |
| F1 Score | **52.7%** |

---

## Project Workflow

- Business Understanding
- Data Quality Assessment & Exploratory Data Analysis
- Fine & Coarse Classing
- Weight of Evidence (WOE) Transformation
- Information Value (IV) Analysis
- Feature Selection & Multicollinearity Assessment
- Logistic Regression Model Development
- Model Evaluation
- Threshold Optimisation
- Lift & KS Analysis
- Score Scaling
- Scorecard Generation
- Customer-Level Scorecard Application

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Jupyter Notebook

---

## Key Takeaways

- Built a fully interpretable **bank-style Probability of Default (PD) Scorecard** using traditional credit risk modelling techniques.
- Demonstrated the complete transformation from **raw customer data → WOE variables → logistic regression → scaled credit score → scorecard generation**.
- Developed a transparent and production-oriented credit scoring framework suitable for customer risk ranking and credit decision-making.

---

## Future Improvements

- Validate the scorecard on an **Out-of-Time (OOT)** dataset.
- Monitor **Population Stability Index (PSI)** to detect model drift after deployment.
- Compare the scorecard with advanced machine learning models such as **XGBoost** and **LightGBM**.
- Incorporate macroeconomic variables to improve model robustness.
- Extend the framework to include **Loss Given Default (LGD)** and **Exposure at Default (EAD)** modelling.
