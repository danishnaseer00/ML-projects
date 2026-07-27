# Credit Card Fraud Detection Model

This repository contains a machine learning model designed to detect fraudulent credit card transactions using an Artificial Neural Network (ANN) with SMOTE (Synthetic Minority Oversampling Technique) to handle class imbalance. The model is implemented in a Google Colab notebook and leverages the Kaggle "Creditcardfraud" dataset.

## Overview
- **Dataset**: Kaggle "Creditcardfraud" dataset with 284,807 transactions, including 492 frauds and 284,315 non-frauds.
- **Features**: 31 columns (Time, V1–V28, Amount, Class).
- **Approach**: Uses SMOTE for oversampling the minority class and an ANN for classification.
- **Environment**: Python 3 in Google Colab.

## Installation
1. Clone the repository
   git clone <repository-url>

Install dependencies:
bashpip install pandas numpy matplotlib scikit-learn tensorflow

Set up Kaggle API:

Upload kaggle.json with your API credentials.
Run the notebook cells to download and unzip the dataset.



## Usage

Open Credit_Card_Fraud_Detection (2).ipynb in Google Colab or Jupyter Notebook.
Execute cells to load data, preprocess, train the model, and evaluate performance.
Adjust the threshold using the provided precision_recall_curve code for optimized results.

## Performance

Initial Metrics:

Accuracy: 99%
Fraud Recall: 0.92
Fraud Precision: 0.18
Fraud F1-Score: 0.30


## Optimized Metrics (with threshold adjustment):

Fraud Precision: 0.87
Fraud Recall: 0.76
Fraud F1-Score: 0.81


## Observations:
Overfitting detected; validation loss stabilizes after epoch 3, mitigated by early stopping.

## Improvements

Add regularization (e.g., Dropout, L2) to reduce overfitting.
Tune the threshold further for better precision-recall balance.
Implement cross-validation for robustness.

