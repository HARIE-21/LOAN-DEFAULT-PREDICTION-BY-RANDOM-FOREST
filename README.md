# LOAN-DEFAULT-PREDICTION-BY-RANDOM-FOREST
# 🏦 Loan Default Prediction Using Random Forest

This project builds a machine learning model to predict whether a loan applicant will default on their loan. Using a **Random Forest Classifier**, the model analyzes various borrower attributes—such as income, credit score, loan amount, and employment history—to assess default risk.

The goal is to provide an explainable, ready-to-use solution for financial institutions to automate and improve their credit risk assessment processes.

---

## 📊 Dataset

The dataset (`Loan_Default.csv`) contains loan application records with the following key features:

| Feature | Description |
|---------|-------------|
| `Income` | Annual income of the applicant |
| `Credit_Score` | Credit score of the applicant |
| `loan_amount` | Requested loan amount |
| `LTV` | Loan-to-value ratio |
| `rate_of_interest` | Interest rate on the loan |
| `term` | Loan term (in months) |
| `Gender`, `age`, `Region` | Demographic attributes |
| `Credit_Worthiness`, `loan_type`, `loan_purpose` | Categorical loan details |
| `Status` | **Target variable** – `1` = Default, `0` = No Default |

> The dataset is provided as a CSV file. The notebook handles missing values, encodes categorical variables, and scales numerical features automatically.

---

## 🚀 Features

- **End-to-end ML pipeline** using `scikit-learn` (imputation, encoding, modeling)
- **Random Forest Classifier** with built-in feature importance
- **Performance metrics**: Accuracy, Precision, Recall, F1-score, ROC-AUC
- **Visualization**: Confusion matrix, ROC curve, and top feature importance bar chart
- **Custom prediction** – test the model with your own sample input
- Fully documented and ready to run in **Jupyter Notebook** or **Google Colab**

---

## 🛠 Installation & Requirements

Make sure you have Python 3.8+ installed. Then install the required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
