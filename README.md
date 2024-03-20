# Titanic Survival Prediction using Extra Trees

This repository contains the implementation of a machine learning model to predict the survival of passengers aboard the Titanic using the Extra Trees algorithm. The model is trained on the Titanic dataset, which contains information about passengers' demographics and ticket details.

## Introduction

The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, the Titanic sank after colliding with an iceberg, resulting in the deaths of thousands of passengers and crew. This project aims to predict the survival of passengers based on various features such as age, sex, ticket class, and fare.

## Methodology

The prediction model utilizes the Extra Trees algorithm, which is an ensemble learning method for classification and regression tasks. Additionally, the K-fold cross-validation with stratified sampling strategy is employed to evaluate the model's performance and ensure robustness.

## Implementation

The implementation consists of the following steps:

1. Data preprocessing: Cleaning and preprocessing the Titanic dataset, handling missing values, and encoding categorical variables.
2. Model training: Training the Extra Trees classifier on the preprocessed dataset.
3. Evaluation: Evaluating the model's performance using K-fold cross-validation with stratified sampling.
4. Prediction: Making predictions on new data to determine the survival of passengers.

## Results

The evaluation results demonstrate the effectiveness of the Extra Trees model in predicting the survival of Titanic passengers. The K-fold cross-validation with stratified sampling strategy ensures reliable performance estimation and model validation.
