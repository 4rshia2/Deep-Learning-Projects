# Titanic Survival Prediction
This repository contains code for predicting the survival of passengers on the Titanic using logistic regression. The prediction model is trained on the Titanic dataset, which is a classic dataset for practicing data analysis and machine learning.
## Introduction
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. This project aims to build a logistic regression model to predict whether a passenger survived the Titanic disaster based on various features such as age, gender, and class.
## Data Preprocessing
In the data preprocessing phase, we perform the following tasks:

* Removal of unnecessary columns, such as PassengerId, Name, Ticket, and Cabin.
* Handling missing values, particularly for the 'Age' and 'Embarked' columns.
* Encoding categorical features using one-hot encoding.
* Standardizing the data for model training.

## Model Training
We train a logistic regression model to predict passenger survival. Model parameters, such as learning rate (ALPHA) and regularization (LAMDA), are fine-tuned to avoid underfitting and overfitting. Cross-validation is used to assess the model's performance.
## Model Evaluation
The model's performance is evaluated using cross-validation. Cost function values are plotted for both training and validation datasets to identify underfitting or overfitting issues. Appropriate model hyperparameters are selected based on the evaluation.
## Prediction
After selecting the best model with optimal hyperparameters, we use it to predict passenger survival on a test dataset. The predictions are saved in a 'Survived' column in the test dataset.
