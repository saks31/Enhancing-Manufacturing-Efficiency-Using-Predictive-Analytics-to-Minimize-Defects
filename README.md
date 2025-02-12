Manufacturing Defect Prediction

Overview

This project aims to reduce manufacturing defects by leveraging Random Forest & GridSearchCV, achieving 95.2% prediction accuracy. By implementing advanced data processing techniques, including SMOTE for class imbalance handling and Chi-Squared feature selection, the model significantly improves quality control through systematic hyperparameter tuning.

Features:

High-accuracy defect prediction using Random Forest.

SMOTE (Synthetic Minority Over-sampling Technique) to balance dataset and improve defect detection.

Chi-Squared test for feature selection, ensuring optimal predictor variables.

GridSearchCV for hyperparameter tuning, optimizing performance and reducing overfitting.

Confusion matrix & classification report for model performance evaluation.

Standardized pipeline for real-time deployment in manufacturing automation systems.

Dataset: 

The dataset contains various manufacturing parameters, including:

Production Volume, Cost, Supplier Quality, Downtime Percentage, Worker Productivity, Safety Incidents, Energy Consumption, and Defect Rate.

The target variable: DefectStatus (0 = No Defect, 1 = Defective).


Best Parameters:

{'max_depth': 20, 'min_samples_split': 2, 'n_estimators': 200}

Accuracy: 95.2%

Precision, Recall, F1-score:

Defective items detection: 96% precision, 99% recall

Non-defective items detection: 91% precision, 77% recall
