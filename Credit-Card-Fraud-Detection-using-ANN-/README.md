<h1 align="center">Credit Card Fraud Detection using ANN</h1>
<p align="center"><img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/TensorFlow-2.x-FF6F00?logo=tensorflow&logoColor=white" alt="TensorFlow"> <img src="https://img.shields.io/badge/Keras-Latest-D00000?logo=keras&logoColor=white" alt="Keras"> <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white" alt="Jupyter"></p>
<p align="center">Fraudulent transaction detection using an Artificial Neural Network with SMOTE oversampling on the Kaggle Credit Card Fraud dataset.</p>

---

## Overview

- **Dataset**: Kaggle "Creditcardfraud" — 284,807 transactions (492 fraud, 284,315 non-fraud)
- **Approach**: ANN with SMOTE (Synthetic Minority Oversampling) to handle class imbalance
- **Features**: 31 columns (Time, V1–V28, Amount, Class)

## Performance

**Before threshold tuning:** Accuracy 99%, Recall 0.92, Precision 0.18, F1 0.30

**After threshold tuning:** Precision 0.87, Recall 0.76, F1 0.81

## Key Takeaways

- Overfitting detected; validation loss stabilizes after epoch 3 with early stopping
- Threshold tuning dramatically improved precision-recall balance
- Further improvements: regularization (Dropout, L2), cross-validation
