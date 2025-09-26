# Logistic-Regression-Classifier(Breast_Cancer_Dataset)
## Project Overview

This project builds a binary classifier using Logistic Regression on the Breast Cancer Wisconsin dataset (from scikit-learn).
The objective is to:
    -Train a logistic regression model
    -Evaluate performance using standard metrics
    -Understand concepts like ROC-AUC, threshold tuning, and the sigmoid function

## Tools & Libraries
-Python 3

-Pandas → data handling

-Matplotlib → plotting

-Scikit-learn → ML model & metrics

## Dataset
Dataset: Breast Cancer Wisconsin Diagnostic Dataset (built-in with scikit-learn).

Classes: 0 → Malignant (cancer)
         1 → Benign (no cancer)
         
Features: 30 numeric attributes describing tumor characteristics.

## Steps Performed
1. Load dataset from sklearn.datasets
2. Train/Test split (80/20)
3. Fit Logistic Regression model
4. Evaluate model using: Confusion Matrix, Precision, Recall, F1-score, ROC-AUC curve
5. Threshold tuning to study precision-recall tradeoff
6. Visualize the sigmoid function to understand probability mapping

## Visualization
- Confusion Matrix → to understand predictions
- ROC Curve → to evaluate classifier performance
- Sigmoid Function → to explain probability mapping

## Concepts
1. ROC–AUC Curve → Model performance across all thresholds
2. Threshold Tuning → Adjusting cutoff probability (default = 0.5) to balance precision & recall
3. Sigmoid Function → Converts linear model output into probabilities between 0 and 1

