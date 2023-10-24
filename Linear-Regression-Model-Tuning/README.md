# Linear Regression Model Tuning
This repository contains a Python implementation of Linear Regression model tuning for regression tasks. The code allows you to experiment with different polynomial degrees and regularization parameters (lambda) to find the best model for your data. The project uses Python, NumPy, and Pandas for data manipulation and visualization.
# Introduction
Linear Regression is a fundamental machine learning algorithm used for regression tasks, and it can be enhanced by adding polynomial features and regularization. This implementation provides the flexibility to experiment with different degrees of polynomial features and different regularization strengths to find the optimal configuration for your dataset.
# Model Tuning
The code allows you to tune two main hyperparameters:

1. Polynomial Degrees (exp): Experiment with different polynomial degrees to capture complex relationships in your data.

2. Regularization Parameter (lambda): Introduce L2 regularization to prevent overfitting. The lambda parameter controls the strength of regularization.

# Results
The key results from running this code are as follows:

* A visualization of MSE for different settings of polynomial degrees and regularization parameters.
* The best configuration with the lowest MSE on the validation dataset.
* The learned weights for the best configuration.
* Predictions on the test dataset using the best configuration.
