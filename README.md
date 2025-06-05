# Wine Classifier Comparison

This project compares the performance of three machine learning classifiers—**SVC (RBF Kernel)**, **Random Forest**, and **AdaBoost**—on the Wine dataset.

## Project Goals

- Perform 10-fold cross-validation
- Compare accuracy across classifiers
- Evaluate multi-class ROC AUC
- Visualize ROC curves for all classes

## Dataset

- Source: UCI Machine Learning Repository (Wine Data)
- Features: 13 chemical measurements
- Target: 3 wine cultivars

## Algorithms Used

- Support Vector Classifier (RBF Kernel)
- Random Forest (max_depth=2)
- AdaBoost Classifier

## Results Summary

- **SVC (RBF)**: Highest accuracy and ROC AUC
- **Random Forest**: Close performance with just depth=2
- **AdaBoost**: Slightly less consistent, still strong
