# Advertising Sales Analysis with MLflow

## Overview
This project analyzes advertising spending across TV, radio, and newspaper channels to understand its impact on sales. We use machine learning models to predict sales based on spending and track model performance using MLflow.

## Dataset
The dataset contains:
- **TV**: Advertising spending on TV campaigns (in thousands of dollars).
- **Radio**: Advertising spending on radio campaigns (in thousands of dollars).
- **Newspaper**: Advertising spending on newspaper campaigns (in thousands of dollars).
- **Sales**: Sales revenue (in thousands of dollars).

## Project Highlights
1. **Data Cleaning**: Outlier removal and data preprocessing.
2. **Model Training**: Using Random Forest, Gradient Boosting, Linear Regression, and KNN Regressor.
3. **Experiment Tracking**: Logging metrics and models with MLflow.

## Usage
1. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
2. Start the MLflow server:
    ```bash
    mlflow ui
    ```
3. Run the main script:
    ```bash
    Impact-of-Media-Advertising.ipynb
    ```
