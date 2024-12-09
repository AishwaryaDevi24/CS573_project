### Predicting Flight Delays Using Data Mining Algorithms

This repository contains the code and resources for the project **"Predicting Flight Delays Using Data Mining Algorithms."** The project focuses on predicting whether a flight will be delayed by more than 15 minutes using a variety of machine learning models, including Logistic Regression, Random Forest, XGBoost, and Support Vector Machines (SVM).

## Overview

Flight delays are a significant challenge for the aviation industry, leading to operational inefficiencies, financial losses, and passenger dissatisfaction. This project addresses the issue by building predictive models using real-world flight data, with enhancements to improve model reliability and real-world applicability.

### Key Features of the Project

- **Dataset**: A subset of the 2022 Kaggle Flight Dataset, containing 200,000 sampled records.
- **Class Imbalance Handling**: Use of SMOTE and Anomaly Detection techniques to address the imbalanced nature of delay data.
- **Temporal Splitting**: Simulating real-world deployment by training on historical data and testing on future data.
- **Model Comparison**: Evaluation of multiple machine learning models to determine the best-performing approach.
- **Evaluation Metrics**: Assessment using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC.

## Methodology

The workflow for this project follows these steps:

1. **Data Preprocessing**:
   - Removal of irrelevant and post-event features to prevent data leakage.
   - Encoding of categorical variables and scaling of numerical features.
2. **Feature Engineering**:
   - Selection of operationally relevant features like scheduled times, airline, and route details.
3. **Class Imbalance Handling**:
   - Comparison of SMOTE oversampling and Anomaly Detection approaches.
4. **Model Training and Evaluation**:
   - Training Logistic Regression, Random Forest, XGBoost, and SVM models.
   - Evaluation using comprehensive performance metrics.

## Results

- **XGBoost** emerged as the top-performing model, achieving:
  - AUC-ROC: 0.87
  - F1-Score: 0.53
- Temporal splitting improved real-world applicability by ensuring models were tested on unseen data.
- Anomaly Detection provided better precision and F1-scores compared to SMOTE for handling class imbalance.


## Dataset

The dataset used in this project is publicly available on Kaggle:
[Kaggle 2022 Flight Dataset](https://www.kaggle.com/code/robikscube/flight-delay-exploratory-data-analysis-twitch).


This project demonstrates the potential of machine learning for improving flight delay predictions and provides a framework for deploying predictive models in real-world airline operations. 
