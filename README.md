# Pima-Indians-Diabetes-prediction-----Logistic-Regression-Project
Diabetes prediction using Logistic Regression with Python, data preprocessing, EDA, and model evaluation.
Logistic Regression project for predicting diabetes using Python, Pandas, Matplotlib, Seaborn, and Scikit-learn.

## Overview

This project performs Logistic Regression on the **Pima Indians Diabetes dataset** to analyze the relationship between different medical and demographic features and the likelihood of diabetes.

The project includes data loading, preprocessing, exploratory analysis, visualization, model training, prediction, and evaluation.

## Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* Jupyter Notebook

## Analysis Performed

* Data loading and preprocessing
* Identifying and handling invalid zero values
* Exploratory data analysis
* Data visualization
* Feature selection
* Train-test splitting with stratification
* Median imputation
* Feature scaling using StandardScaler
* Logistic Regression model training
* Model prediction
* Model evaluation
* Confusion matrix analysis
* Logistic Regression coefficient interpretation

## Dataset

The project uses the **Pima Indians Diabetes dataset**, which contains medical diagnostic measurements used to predict whether a patient has diabetes.

The target variable is **Outcome**, where:

* `0` → No diabetes
* `1` → Diabetes

The dataset contains features such as pregnancies, glucose level, blood pressure, skin thickness, insulin, BMI, diabetes pedigree function, and age.

## Model Evaluation

The Logistic Regression model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC
* Confusion Matrix

### Results

* **Accuracy:** 74.68%
* **Precision:** 60.87%
* **Recall:** 77.78%
* **F1-score:** 68.29%
* **ROC-AUC:** 82.72%

**Confusion Matrix:**

* True Negatives: 73
* False Positives: 27
* False Negatives: 12
* True Positives: 42

## Project File

The main analysis and Logistic Regression implementation is available in the Jupyter Notebook:

`Logistic_Regression_Diabetes.ipynb`
