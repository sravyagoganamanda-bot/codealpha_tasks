# Disease Prediction from Medical Data

## Project Overview

This project focuses on predicting the likelihood of disease using machine learning techniques on medical data. The Breast Cancer dataset was used to train and evaluate multiple classification models. The objective is to identify whether a tumor is benign or malignant based on various medical measurements.

## Objective

* Predict disease outcomes using patient medical data.
* Compare multiple machine learning classification algorithms.
* Select the best-performing model based on accuracy.

## Dataset

The project uses the Breast Cancer dataset available through Scikit-Learn, which contains features related to tumor characteristics such as radius, texture, perimeter, area, and smoothness.

## Machine Learning Algorithms Used

* Logistic Regression
* Support Vector Machine (SVM)
* Random Forest
* XGBoost

## Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 97.37%   |
| SVM                 | 98.25%   |
| Random Forest       | 96.49%   |
| XGBoost             | 95.61%   |

### Best Model

Support Vector Machine (SVM) achieved the highest accuracy of 98.25%.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Joblib

## Project Workflow

1. Data Loading and Exploration
2. Data Preprocessing
3. Feature Scaling
4. Train-Test Split
5. Model Training
6. Performance Evaluation
7. Model Comparison
8. Model Saving

## Output

The trained best-performing model is saved as:

best_model.pkl

## Conclusion

The project successfully demonstrates the use of machine learning techniques for disease prediction. Among the evaluated algorithms, SVM delivered the highest predictive performance with an accuracy of 98.25%.
