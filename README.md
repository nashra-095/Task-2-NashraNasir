# Data Classification Using AI 

## Project Overview

This project implements an end-to-end **Supervised Machine Learning Classification Pipeline** using Python, Pandas, and Scikit-Learn. The objective is to classify e-commerce transactions based on their transaction status using the **K-Nearest Neighbors (KNN)** algorithm.

The project focuses on data preprocessing, feature engineering, feature scaling, model training, and performance evaluation to build a structured and reliable classification workflow.

## Project Architecture

The project follows the **Input → Process → Output (IPO)** framework.

### 1. Input
- Dataset: `Dataset for Data Analytics.xlsx`
- Format: Excel (.xlsx)
- Data: E-commerce transaction records containing numerical, categorical, and date-related features.

### 2. Process
The dataset goes through the following machine learning pipeline:

- **Data Preprocessing:** Handling missing values in categorical features.
- **Date Feature Extraction:** Extracting meaningful features from date columns.
- **Categorical Encoding:** Applying One-Hot Encoding to convert categorical data into numerical representations.
- **Feature Scaling:** Using `StandardScaler` to standardize numerical features.
- **Model Training:** Training a K-Nearest Neighbors (KNN) classifier with K=5.
- **Modular Pipeline:** Using `ColumnTransformer` to organize numerical and categorical preprocessing.

### 3. Output
- Predicted transaction statuses.
- Classification performance metrics.
- Confusion matrix visualization.
- Class-wise Precision, Recall, and F1-Score.

## Key Features

- **End-to-End ML Pipeline:** Integrates preprocessing, feature engineering, training, and evaluation.
- **Automated Preprocessing:** Handles missing values, categorical encoding, and numerical standardization.
- **Feature Normalization:** Standardizes numerical features to prevent variables with larger scales from dominating distance calculations.
- **KNN Classification:** Uses a distance-based supervised learning algorithm to classify transaction records.
- **Model Evaluation:** Analyzes classification performance through multiple evaluation metrics.
- **Data Visualization:** Uses a confusion matrix heatmap to examine correct and incorrect predictions.

## Technologies & Libraries

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- OpenPyXL

## Machine Learning Algorithm

**K-Nearest Neighbors (KNN)**

KNN is a supervised machine learning algorithm that classifies a data point based on the majority class among its nearest neighbors.

- Algorithm: K-Nearest Neighbors
- Number of Neighbors: K = 5
- Learning Type: Supervised Learning
- Task: Multi-class Classification

## Model Evaluation

The trained model is evaluated using:

| Metric | Purpose |
|---|---|
| Precision | Measures how many predicted positive classifications are correct. |
| Recall | Measures how many actual class instances are correctly identified. |
| F1-Score | Balances precision and recall. |
| Confusion Matrix | Shows correct and incorrect class predictions. |

## Project Workflow

1. Load the Excel dataset.
2. Explore and understand the data.
3. Identify numerical and categorical features.
4. Handle missing values.
5. Extract useful date-related features.
6. Encode categorical variables.
7. Standardize numerical features.
8. Split data into training and testing sets.
9. Train the KNN classification model.
10. Generate predictions.
11. Evaluate model performance.
12. Visualize results using a confusion matrix.

## Project Objective

The main objective is to gain practical experience in building a complete supervised machine learning classification pipeline while understanding how data preprocessing, feature engineering, and feature scaling contribute to model performance.


