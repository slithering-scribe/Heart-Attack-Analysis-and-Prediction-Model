# Heart Attack Prediction Model

1. Introduction
Heart disease is one of the leading causes of death worldwide. Predicting heart attacks using data can enable timely interventions and improve patient outcomes. This project aims to build a model that accurately predicts the likelihood of a heart attack based on patient data.

2. Data Description
Source: The dataset was sourced from Kaggle.

Attributes: The dataset includes features such as age, sex, cholesterol levels, resting blood pressure, etc., and the target variable indicating the likelihood of a heart attack.

Preprocessing: Handled missing values, removed outliers, and scaled features using StandardScaler.

3. Exploratory Data Analysis (EDA)
Visualizations: Plotted histograms, pair plots, and correlation matrices to understand the relationships between features.

Outliers & Distribution: Identified and addressed outliers. Ensured the data distribution was suitable for model training.

4. Model Selection
Why Logistic Regression?: Logistic Regression was chosen for its simplicity and effectiveness in binary classification problems. Additionally, models like Random Forest were tested to ensure robust performance.

Initial Results: Logistic Regression gave a solid starting accuracy of 85%.

5. Hyperparameter Tuning
Grid Search Process: Used GridSearchCV with a parameter grid to find the best hyperparameters for Logistic Regression.

Parameter Grid: {'C': [0.01, 0.1, 1, 10, 100], 'solver': ['newton-cg', 'lbfgs', 'liblinear']}

Best Parameters: {'C': 0.01, 'solver': 'liblinear'}

6. Evaluation Metrics
Accuracy: The tuned Logistic Regression model achieved an accuracy of 88.5%.

Precision, Recall, F1-Score: Achieved high precision and recall with balanced F1-scores for both classes.


Logistic Regression Accuracy: 88.5%
Classification Report:
             precision    recall  f1-score   support
         0       0.89      0.86      0.88        29
         1       0.88      0.91      0.89        32
  accuracy                           0.89        61
 macro avg       0.89      0.88      0.88        61
weighted avg 0.89 0.89 0.89 61


Confusion Matrix: Correctly classified most instances with minimal errors.

Confusion Matrix:
[[25  4]
 [ 3 29]]
 
7. Conclusion
The Logistic Regression model, after hyperparameter tuning, demonstrated a strong ability to predict heart attacks with an accuracy of 88.5%. The high precision and recall indicate effective identification of at-risk individuals, making this model a valuable tool in clinical settings. Future work may involve exploring additional features, more advanced models, or integrating real-time data for continuous improvement.
