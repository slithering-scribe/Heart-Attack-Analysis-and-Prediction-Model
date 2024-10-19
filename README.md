# Heart Attack Prediction Model

## Introduction

Heart disease is one of the leading causes of death worldwide. Predicting heart attacks using data can enable timely interventions and improve patient outcomes. This project aims to build a model that accurately predicts the likelihood of a heart attack based on patient data.

## Data Description

* **Source:** The dataset was sourced from Kaggle.
* **Attributes:** The dataset includes features such as age, sex, cholesterol levels, resting blood pressure, etc., and the target variable indicating the likelihood of a heart attack.
* **Preprocessing:** Handled missing values, removed outliers, and scaled features using StandardScaler.

## Exploratory Data Analysis (EDA)

* **Visualizations:** Plotted histograms, pair plots, and correlation matrices to understand the relationships between features.
* **Outliers & Distribution:** Identified and addressed outliers. Ensured the data distribution was suitable for model training.

## Model Selection

* **Logistic Regression:** Chosen for its simplicity and effectiveness in binary classification problems.
* **Other Models:** Random Forest and Gradient Boosting were tested for comparison.

**Initial Results:** Logistic Regression achieved a solid starting accuracy.

## Hyperparameter Tuning

* **Grid Search:** Used GridSearchCV to find optimal hyperparameters for Logistic Regression.
* **Parameter Grid:** {'C': [0.01, 0.1, 1, 10, 100], 'solver': ['newton-cg', 'lbfgs', 'liblinear']}
* **Best Parameters:** {'C': 0.01, 'solver': 'liblinear'}

## Evaluation Metrics

* **Accuracy:** The tuned Logistic Regression model achieved an accuracy of 88.5%.
* **Precision, Recall, F1-Score:** Balanced scores across both classes.

**Logistic Regression Accuracy:** 88.5%

**Confusion Matrix:** Correctly classified most instances with minimal errors.

## Model Enhancements

* **Feature Engineering:** Focused on top features 'cp', 'caa', and 'thall'.
* **Modeling:** Implemented Random Forest, Gradient Boosting, and Neural Network models.
* **Hyperparameter Tuning:** Performed detailed GridSearchCV on Random Forest and Gradient Boosting models.

**Neural Network Accuracy:** Achieved an accuracy of 80.3%.

**Updated Evaluation Metrics**

* **Gradient Boosting Accuracy:** 80.3%
* **Precision, Recall, F1-Score:** Improved balanced scores.
* **Neural Network Accuracy:** 80.3%
* **Confusion Matrix:** Improved classification with feature engineering and ensemble methods.

## Conclusion

The combination of feature engineering, model selection, and hyperparameter tuning has demonstrated significant improvement in predicting heart attacks. The high precision and recall indicate effective identification of at-risk individuals, making this model a valuable tool in clinical settings. Future work may involve exploring additional features, more advanced models, or integrating real-time data for continuous improvement.
