## 🏥 Hospital Mortality Prediction Model

This project develops a machine learning model to predict in-hospital mortality risk using patient records. By leveraging logistic regression and ensemble methods, the model assists in early identification of high-risk patients, supporting better decision-making in healthcare.

## 📊 Project Overview

Dataset: 50,000 patient records (clinical + demographic features).

Objective: Predict likelihood of patient mortality during hospital stay.

Approach: Applied data preprocessing, feature engineering, and multiple ML models.

Key Model: Logistic Regression (with ensemble baselines).

## 🚀 Performance Metrics

ROC AUC: 0.85 (vs. 0.50 random baseline)

Train Accuracy: 92.3%

Test Accuracy: 92.2%

10-Fold Cross-Validation Accuracy: Mean 0.921 (std ~0.002)

These results indicate strong model generalization and significant improvement over chance-level prediction.

## 🛠️ Tech Stack

Languages: Python

Libraries:

pandas, numpy (data preprocessing)

scikit-learn (modeling, evaluation)

matplotlib, seaborn (visualization)

## 📈 Results Visualization

Example ROC curve comparison between model and baseline:

<img width="702" height="547" alt="3201b2d5-3335-4cb5-867d-498de1b8b887" src="https://github.com/user-attachments/assets/f0f25c80-e49f-47eb-bfaf-f99b0d620412" />
