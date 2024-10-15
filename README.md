# Loan Prediction Project 🚀

This project aims to predict whether a loan will be approved or not based on various features such as income, education level, marital status, and credit history. The model is built using **Support Vector Machine (SVM)** for classification.

## 📋 Table of Contents
- [Introduction](#introduction)
- [Objective](#objective)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Conclusion](#conclusion)
- [Author](#author)
- [License](#license)

## 💡 Introduction

Loan approval is a key decision-making process for banks and financial institutions. By leveraging machine learning models, we can assist in automating this decision, improving both speed and accuracy. This project uses historical loan data to train a predictive model.

## 🎯 Objective

The objective of this project is to develop a machine learning model to predict whether an individual's loan will be **Approved** or **Rejected** based on their demographic and financial details.

## 📊 Dataset

The dataset used in this project is sourced from Kaggle: [Loan Prediction Dataset](https://www.kaggle.com/datasets/ninzaami/loan-predication).

### Features:
- **Gender**: Male/Female
- **Married**: Applicant's marital status
- **Dependents**: Number of dependents
- **Education**: Applicant’s education level (Graduate/Not Graduate)
- **Self_Employed**: Applicant's employment status (Yes/No)
- **ApplicantIncome**: Income of the applicant
- **CoapplicantIncome**: Income of the co-applicant (if any)
- **LoanAmount**: Loan amount in thousands
- **Loan_Amount_Term**: Term of loan in months
- **Credit_History**: History of credit payments (1: good, 0: bad)
- **Property_Area**: Urban/Semiurban/Rural
- **Loan_Status**: Whether the loan was approved (Y) or not (N) – this is the target variable.

## 🏗️ Project Structure

```bash
Loan-Prediction/
│
├── loan_prediction.ipynb      # Jupyter Notebook containing all the code
├── README.md                  # Project documentation
├── loan.csv                   # Dataset (download from Kaggle)
└── images/                    # Directory for any visuals used (optional)
```
## ▶️ Usage:
Open the loan_prediction.ipynb file in Jupyter Notebook or any other IDE, and run all the cells. You will see the data preprocessing, model training, testing, and prediction steps in action.

To predict the loan status for a new user, update the user_input list with their details and rerun the prediction section in the notebook.

## 📊 Results
* Training Accuracy: 79.8%
* Test Accuracy: 77.2%
These results indicate a reasonably accurate model. However, further optimization and hyperparameter tuning can potentially improve the performance.

## 🔍 Conclusion
This project demonstrates how machine learning models can be applied to predict loan approval based on customer details. The model is built using Support Vector Machine (SVM) with reasonable accuracy. This prediction system can help financial institutions make quicker decisions.

⭐️ If you like this project, feel free to give it a star on GitHub!
