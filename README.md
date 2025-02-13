# Manufacturing Defect Prediction

This project leverages machine learning techniques to predict and reduce manufacturing defects, achieving 95.2% accuracy. By implementing Random Forest & GridSearchCV, along with advanced data preprocessing techniques like SMOTE for class imbalance handling and Chi-Squared feature selection, this model significantly improves quality control and optimizes production processes.

## Key Features

- High-accuracy defect prediction using Random Forest.

- SMOTE (Synthetic Minority Over-sampling Technique) for balancing the dataset and improving defect detection.

- Chi-Squared test for feature selection, ensuring optimal predictor variables.

- GridSearchCV for hyperparameter tuning, enhancing model performance and reducing overfitting.

- Confusion Matrix & Classification Report for comprehensive model evaluation.

- Standardized pipeline designed for real-time deployment in manufacturing automation systems.

## Technologies Used

- Python

- Pandas & NumPy for data processing

- Scikit-learn for machine learning and model evaluation

- Imbalanced-learn (SMOTE) for handling class imbalance

- Matplotlib & Seaborn for data visualization

## Main Components

- Data Processing & Feature Selection:

- Handles missing values and performs data cleaning.

- Applies Chi-Squared tests to select the most relevant manufacturing parameters.

### Model Training & Optimization:

- Uses Random Forest for classification.

- Performs hyperparameter tuning with GridSearchCV to enhance accuracy.

- Balances the dataset using SMOTE to improve defect detection rates.

### Model Evaluation & Visualization:

- Generates confusion matrix and classification reports.

- Plots feature importance charts to highlight key defect predictors.

- Implements precision-recall curves for model performance analysis.

## Dataset

- The dataset contains key manufacturing parameters including:

Production Volume, Cost, Supplier Quality, Downtime Percentage, Worker Productivity, Safety Incidents, Energy Consumption, and Defect Rate.

Target Variable: DefectStatus (0 = No Defect, 1 = Defective).

## Model Evaluation

- Best Parameters Identified by GridSearchCV:

{'max_depth': 20, 'min_samples_split': 2, 'n_estimators': 200}

Accuracy: 95.2%

- Precision, Recall, F1-score:

Defective items detection: 96% precision, 99% recall.

Non-defective items detection: 91% precision, 77% recall.

## Results & Visualization

- Confusion Matrix: Displays correct vs. incorrect predictions.

- Feature Importance Plot: Highlights which manufacturing parameters contribute most to defects.

- Precision-Recall Curve: Evaluates model effectiveness under different thresholds.

## Future Enhancements

- Deploying the model using Flask or FastAPI for real-time defect detection.

- Integrating with IoT sensors to analyze manufacturing line data in real-time.

- Expanding the dataset to incorporate additional manufacturing variables for improved accuracy.

- Exploring deep learning approaches for even higher precision defect classification.
