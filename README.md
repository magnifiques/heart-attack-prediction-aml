# Heart Disease Prediction Using Machine Learning Ensembles

## Overview

This project explores multiple machine learning methodologies to predict heart disease based on patient data. It implements and compares several classification models, including base learners and ensemble techniques like **Bagging** and **Stacking** to enhance predictive accuracy and robustness.

By leveraging ensemble learning, feature selection, and hyperparameter tuning, this work achieves high performance in classification metrics, demonstrating the potential of machine learning in cardiovascular health prediction.

---

## Features

- Implements base models: Decision Trees, Random Forest, K Nearest Neighbors (KNN), Support Vector Machines (SVM), Logistic Regression, Naive Bayes.
- Applies ensemble techniques:
  - **Bagging** (Bootstrap Aggregating) with Decision Trees to reduce variance and overfitting.
  - **Stacking** combining diverse base models with a meta-classifier to optimize predictions.
- Data preprocessing and feature selection to improve model performance.
- Evaluation using comprehensive metrics: Accuracy, Precision, Recall, F1 Score, Specificity, ROC AUC.
- Confusion matrices to visualize classification results.
- Hyperparameter tuning for optimized model performance.

---

## Performance Highlights

| Model                           | Accuracy | Precision | Recall  | F1 Score | ROC AUC  |
| -------------------------------| -------- | --------- | ------- | -------- | -------- |
| Random Forest (Base)            | 97.5%    | 98.0%     | —       | 97.6%    | —        |
| Tuned K Nearest Neighbors       | 99.0%    | —         | 100%    | —        | —        |
| Bagging Ensemble (Decision Tree)| 96.10%   | 95.24%    | 97.09%  | 98.52%   | 98.54%   |
| Stacking Ensemble               | 97.56%   | 100%      | 95.15%  | 97.51%   | 97.57%   |

*Note: Dash (—) indicates metric not specifically reported for that model.*

---

## Getting Started

### Prerequisites

- Python 3.7+
- scikit-learn
- pandas
- numpy
- matplotlib (for plotting confusion matrices)

Install dependencies using:

```bash
pip install -r requirements.txt
