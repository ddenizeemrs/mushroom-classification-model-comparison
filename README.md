# Mushroom Classification Model Comparison

A machine learning classification project developed in **MATLAB** to compare multiple models for predicting whether a mushroom is **edible** or **poisonous**.

## Project Overview

The project uses a mushroom classification dataset containing categorical features describing different mushroom characteristics.

The target variable contains two classes:

- `e` — Edible
- `p` — Poisonous

The main objective is to compare the performance of three different machine learning classifiers.

## Models Compared

The following models were trained and evaluated:

- Decision Tree
- Efficient Logistic Regression
- K-Nearest Neighbors (KNN)

## Evaluation Strategy

The project uses:

- 5-Fold Cross-Validation
- Separate Test Dataset

This allows the models to be evaluated both during validation and on previously unseen test data.

## Evaluation Metrics

The models were compared using:

- Accuracy
- Confusion Matrix
- Precision
- Sensitivity / Recall
- Specificity
- F1-score
- G-mean
- ROC Curve
- AUC

## Model Performance

### Decision Tree

Test performance:

- Accuracy: 100.00%
- Precision: 100.00%
- Recall: 100.00%
- Specificity: 100.00%
- F1-score: 100.00%
- G-mean: 100.00%

### Efficient Logistic Regression

Test performance:

- Accuracy: 97.74%
- Precision: 97.62%
- Recall: 97.70%
- Specificity: 97.78%
- F1-score: 97.66%
- G-mean: 97.74%

### K-Nearest Neighbors

Test performance:

- Accuracy: 99.88%
- Precision: 100.00%
- Recall: 99.74%
- Specificity: 100.00%
- F1-score: 99.87%
- G-mean: 99.87%

## Critical Classification Error

In this problem, the most important error is classifying a **poisonous mushroom as edible**.

For this reason, model selection was based not only on overall accuracy, but also on:

- False negatives
- Confusion matrix results
- Recall
- F1-score
- ROC and AUC performance

## Results

The Decision Tree achieved perfect test performance on the evaluated dataset.

KNN also achieved very high performance, with only a small number of classification errors.

Logistic Regression produced slightly lower results but still achieved strong overall performance.

## Technologies

- MATLAB
- Classification Learner
- Machine Learning
- Supervised Learning
- Classification

## Documentation

The complete project report includes model results, confusion matrices, ROC curves and performance comparisons.

[View Project Report](./project-report.pdf)

## Author

**Deniz Emre Baş**
