# Experiment Results Analysis: Text Classification Models

## Overview
This document summarizes the performance of various machine learning models used for sentiment classification on a Kaggle dataset. The models evaluated include Multinomial Naive Bayes, Decision Tree, Random Forest, Support Vector Machine, Logistic Regression, and K-Nearest Neighbors (KNN). 

## K-Nearest Neighbors (KNN)
K-Nearest Neighbors is a simple, instance-based learning algorithm that classifies new instances based on the majority class among their k-nearest neighbors. The algorithm is non-parametric and does not assume any underlying distribution of the data. It is widely used due to its simplicity and effectiveness, especially in classification tasks.

## Model Performance

### 1. Multinomial Naive Bayes
- **Accuracy**: 0.80
- **Classification Report**:
          precision    recall  f1-score   support

     Neg       0.89      0.43      0.58       288
     Pos       0.78      0.97      0.87       612

accuracy                           0.80       900
macro avg 0.83 0.70 0.72 900
weighted avg 0.82 0.80 0.78 900

### 2. Decision Tree
- **Accuracy**: 0.93
- **Classification Report**:
          precision    recall  f1-score   support

     Neg       0.93      0.84      0.88       288
     Pos       0.93      0.97      0.95       612

accuracy                           0.93       900
macro avg 0.93 0.90 0.91 900
weighted avg 0.93 0.93 0.93 900

### 3. Random Forest
- **Accuracy**: 0.90
- **Classification Report**:
          precision    recall  f1-score   support

     Neg       0.94      0.75      0.83       288
     Pos       0.89      0.98      0.93       612

accuracy                           0.90       900
macro avg 0.91 0.86 0.88 900
weighted avg 0.91 0.90 0.90 900

### 4. Support Vector Machine
- **Accuracy**: 0.87
- **Classification Report**:
          precision    recall  f1-score   support

     Neg       0.92      0.64      0.76       288
     Pos       0.85      0.97      0.91       612

accuracy                           0.87       900
macro avg 0.89 0.81 0.83 900
weighted avg 0.87 0.87 0.86 900

### 5. Logistic Regression
- **Accuracy**: 0.87
- **Classification Report**:
          precision    recall  f1-score   support

     Neg       0.96      0.61      0.74       288
     Pos       0.84      0.99      0.91       612

accuracy                           0.87       900
macro avg 0.90 0.80 0.83 900
weighted avg 0.88 0.87 0.86 900

### 6. K-Nearest Neighbors
- **Accuracy**: 0.79
- **Classification Report**:
          precision    recall  f1-score   support

     Neg       0.74      0.55      0.63       288
     Pos       0.81      0.91      0.86       612

accuracy                           0.79       900
macro avg 0.78 0.73 0.74 900
weighted avg 0.79 0.79 0.79 900

## Conclusion
In this experiment, the Decision Tree model achieved the highest accuracy of 0.93, followed closely by Random Forest at 0.90. K-Nearest Neighbors had the lowest accuracy at 0.79, indicating that while KNN is simple to implement, it may not be the best choice for this dataset compared to other algorithms. Overall, the results highlight the effectiveness of different machine learning techniques for sentiment classification.
