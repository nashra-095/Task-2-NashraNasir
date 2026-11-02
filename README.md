Data Classification Using AI (DecodeLabs Project 2)An end-to-end supervised machine learning pipeline built with Python, Pandas, and Scikit-Learn to preprocess tabular data, execute feature engineering, and train a K-Nearest Neighbors (KNN) model for transaction status classification.
Project ArchitectureThe pipeline strictly adheres to the Input → Process → Output (IPO) framework:Input: Tabular dataset (Dataset for Data Analytics.xlsx) containing e-commerce transactions.
Process: Automated date feature extraction, categorical missing-value imputation, one-hot encoding, numerical feature standardization (StandardScaler), and distance-based KNN classification ($K=5$).
Output: Predicted transaction statuses, model evaluation metrics (Precision, Recall, F1-Score), and visual confusion matrix heatmaps.
Key FeaturesModular Pipelines: Structured numerical and categorical preprocessing built using Scikit-Learn ColumnTransformer
Feature Normalization: Standardizes numerical features ($\mu = 0, \sigma = 1$) to eliminate scale bias in Euclidean distance calculations.
Supervised Machine Learning:
Implements K-Nearest Neighbors to identify patterns across multi-class transaction categories.
Robust Evaluation: Comprehensive validation via confusion matrix analysis and class-level metric reporting.
