# Breast-Cancer-Detection-Using-ML-AI
This project applies machine learning models—Logistic Regression, Decision Tree, and Random Forest—to detect breast cancer from cell image features. The dataset is preprocessed, models are trained and evaluated, and the best-performing model is identified for accurate cancer detection.
Project Overview
Data Preprocessing:

Loading the Dataset: The dataset is loaded from a CSV file.
Inspecting Columns: Column names and data types are inspected to ensure proper understanding of the dataset.
Encoding Categorical Variables: Non-numeric columns (e.g., categorical data like 'M' for malignant and 'B' for benign) are converted to numeric using label encoding.
Model Training:

Logistic Regression: A simple yet powerful linear model is used for binary classification.
Decision Tree: A tree-based model that splits the data into subsets based on feature values.
Random Forest: An ensemble model that combines multiple decision trees to improve accuracy and robustness.
Model Evaluation:

Accuracy Scores: The training accuracy of each model is calculated and printed.
Test Set Evaluation: The models are also evaluated on a separate test set to assess their performance on unseen data.
Correlation Analysis:

Correlation Matrix: The correlation matrix of the features is computed to understand the relationships between different features.
