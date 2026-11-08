# M.Tech AIML - Machine Learning Assignment 2

## a. Problem Statement
Implementation, evaluation, and deployment of 5 supervised classification models to diagnose breast cancer tumors (malignant vs benign) using cell nuclei characteristics, paired with an interactive Streamlit application.

## b. Dataset Description
* **Dataset:** Breast Cancer Wisconsin (Diagnostic) Dataset
* **Features:** 30 numerical attributes
* **Instances:** 569 samples
* **Target:** Binary classification (0 = Malignant, 1 = Benign)

## c. GitHub Repository Link
https://github.com/your-username/ml-assignment-2

## d. Models Used & Comparison Table
| ML Model Name | Accuracy | AUC | Precision | Recall | F1 | MCC |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Logistic Regression** | 0.9825 | 0.9954 | 0.9861 | 0.9861 | 0.9861 | 0.9623 |
| **Decision Tree** | 0.9123 | 0.9157 | 0.9559 | 0.9028 | 0.9286 | 0.8174 |
| **KNN** | 0.9561 | 0.9788 | 0.9589 | 0.9722 | 0.9655 | 0.9054 |
| **Naive Bayes** | 0.9386 | 0.9878 | 0.9452 | 0.9583 | 0.9517 | 0.8676 |
| **Support Vector Machine** | 0.9825 | 0.9950 | 0.9861 | 0.9861 | 0.9861 | 0.9623 |

## e. Observations on Model Performance
| ML Model Name | Observation about model performance |
| :--- | :--- |
| **Logistic Regression** | Achieved outstanding performance (98.25% accuracy) by leveraging scaled linear boundaries. |
| **Decision Tree** | Exhibited higher variance and lower generalization accuracy (91.23%). |
| **KNN** | Captured local patterns effectively after feature scaling, achieving 95.61% accuracy. |
| **Naive Bayes** | Provided fast, stable probabilistic classification with 93.86% accuracy. |
| **Support Vector Machine** | Tied for top performance (98.25% accuracy, 0.9950 AUC) via optimal margin separation. |
| **Overall Winner** | **Logistic Regression & Support Vector Machine** (tied for highest accuracy and MCC). |