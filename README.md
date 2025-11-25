# Diabetes-readmission-prediction
Diabetes readmission analysis using multiple classifiers, focusing on handling class imbalance and evaluating model performance.

Objective

Predict whether a patient is likely to be readmitted to the hospital based on medical history, lab results, medications, and hospitalization records. This helps healthcare providers implement preventive measures for high-risk patients.

Dataset

Name: Diabetes Readmission Dataset
Source: Kaggle – Diabetes 130-US hospitals (1999-2008)
Description: Contains patient medical records, including demographics, lab results, diagnoses, medications, and previous admissions. The target variable is readmitted.

Models Used
The following machine learning models were implemented:
Random Forest Classifier – Robust against overfitting; handles both numerical and categorical data.
Logistic Regression – Simple and interpretable; serves as a good baseline.
Gradient Boosting Classifier – Improves accuracy on structured data.
XGBoost Classifier – Optimized gradient boosting for speed and performance.
Support Vector Machine (SVM) – Effective in high-dimensional spaces for class separation.

Model Evaluation
Models were evaluated using accuracy, precision, recall, and F1-score.
Random Forest (Best Model)
Accuracy: 88.83%
Precision: 0.89 (class 0), 0.43 (class 1)
Recall: 1.00 (class 0), 0.00 (class 1)
F1-Score: 0.94 (class 0), 0.01 (class 1)

The Random Forest model was selected as the best-performing model due to its higher overall accuracy and capability to capture complex relationships in the data. Performance metrics for other models are available in the notebook.
