# Autism Prediction

## Overview

Welcome to the Autism Prediction project! This repository houses a robust machine learning model designed to predict whether an individual may have autism. The model is trained on a dataset comprising 800 observations, with features ranging from behavioral scores to demographic information. The target variable, 'Class/ASD,' indicates the presence or absence of autism.

## Project Structure

- **variant_2_autism_prescription**: Central directory for the project.
  - **input**: Holds essential input data for training and validation.
    - **test.csv**: Test dataset.
    - **train.csv**: Training dataset.
  - **finalmodel.sav**: Serialized model file, capturing the trained model's state.
  - **hw3.ipynb**: Interactive Jupyter Notebook containing comprehensive code for data preprocessing, model training, and evaluation.
  - **result.csv**: Predictions for the test dataset.

## Prerequisites

Ensure you have all the necessary dependencies installed before running the code. Refer to the Jupyter Notebook file for a detailed list of required libraries.

## How to Use

Embark on your autism prediction journey by following these steps:
1. Open and explore the `hw3.ipynb` Jupyter Notebook to review the code.
2. Execute the code cells within the notebook for data preprocessing, model training, and evaluation

## Model Training

The heart of the project lies in a Bagging Classifier with a Decision Tree as the base estimator. Fine-tuning of hyperparameters was achieved through GridSearchCV to attain optimal performance.

## Addressing Imbalance

Class imbalance is a common challenge in classification tasks. In this project, the SMOTE (Synthetic Minority Over-sampling Technique) method was employed to generate synthetic samples, significantly enhancing the model's performance.

## Evaluation Metrics

The model's effectiveness is evaluated using a suite of metrics, including accuracy, precision, recall, F1 score, and ROC AUC. Special emphasis is placed on recall, considering its critical role in this classification task.

## Results

The pinnacle achievement of the model includes a remarkable recall of 0.9 on the validation sample and an impressive ROC AUC of 0.862. The serialized model (`finalmodel.sav`) is provided for your convenience.

## Conclusion

In conclusion, this project undertakes the critical task of autism prediction through advanced machine learning techniques. 

This project not only delivers a functional autism prediction model but also serves as an educational resource for understanding the intricacies of classification tasks, handling imbalanced datasets, and fine-tuning machine learning models.


