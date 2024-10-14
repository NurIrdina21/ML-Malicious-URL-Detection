# Malicious URL Detection Model

## Overview

This project implements an ensemble model designed to enhance the detection of malicious URLs by leveraging the strengths of multiple classifiers. The evaluated models include:

- Decision Tree Classifier
- Random Forest Classifier
- AdaBoost Classifier
- KNeighbors Classifier
- SGD Classifier
- ExtraTrees Classifier
- GaussianNB
- XGBClassifier

## Model Approach

The ensemble approach employs a **Voting Classifier** with hard voting, combining the top four performing models to improve predictive performance. This integration captures a broader range of patterns and features associated with malicious URLs, enhancing the overall detection capability.

## Data Collection and Preparation

The final model utilizes a Kaggle dataset containing both benign and malicious URLs. The process involves:

1. **Feature Extraction**: Relevant features are extracted to create balanced and imbalanced datasets.
2. **Data Splitting**: The dataset is divided into training (80%) and testing (20%) sets.
3. **Model Training**: Various classifiers are trained, and the best performers are selected for the ensemble model.

## Evaluation

The ensemble classifier is evaluated using **StratifiedKFold cross-validation** with 5 folds, ensuring reliability and robustness in the predictions. The accompanying flowchart illustrates the process, highlighting the use of ensemble learning, hard voting, and data balancing techniques to improve malicious URL classification.


![image](https://github.com/user-attachments/assets/9d6d8403-92aa-4ff5-bdf8-2b8981d50e0d)


Project by: Nur Irdina Binti Hassan

Multimedia University, Cyberjaya
