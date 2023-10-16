# Random Forest for Credit Default Prediction

This repository contains a Python implementation of a Random Forest model used to predict credit defaults. Credit default prediction is a critical problem in the banking and risk analytics industry, and this model leverages various attributes such as demographic data and behavioral data to make predictions.

## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Data Understanding and Cleaning](#data-understanding-and-cleaning)
- [Data Preparation and Model Building](#data-preparation-and-model-building)
- [Default Hyperparameters](#default-hyperparameters)
- [Hyperparameter Tuning](#hyperparameter-tuning)
  - [Tuning max_depth](#tuning-max_depth)
  - [Tuning n_estimators](#tuning-n_estimators)
  - [Tuning max_features](#tuning-max_features)
  - [Tuning min_samples_leaf](#tuning-min_samples_leaf)
  - [Tuning min_samples_split](#tuning-min_samples_split)
  - [Grid Search for Optimal Hyperparameters](#grid-search-for-optimal-hyperparameters)
- [Final Model](#final-model)
- [Evaluation](#evaluation)
- [Contributing](#contributing)

## Introduction

In this project, we aim to build a Random Forest model to predict whether a customer is likely to default on a credit. We utilize demographic data and behavioral data as features for prediction.

## Getting Started

To get started with this project, you'll need Python and the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these libraries using the following command:



## Data Understanding and Cleaning

We start by understanding the dataset and performing any necessary data cleaning operations. This includes reading the dataset, checking for missing values, and handling any anomalies.

## Data Preparation and Model Building

Next, we prepare the data for model building. This involves separating the features and the target variable, and splitting the data into training and testing sets.

## Default Hyperparameters

We begin by fitting a Random Forest model using default hyperparameters and evaluate its performance.

## Hyperparameter Tuning

We explore various hyperparameters of the Random Forest model to find the optimal combination for improved performance. This includes tuning `max_depth`, `n_estimators`, `max_features`, `min_samples_leaf`, and `min_samples_split`.

## Grid Search for Optimal Hyperparameters

We conduct a grid search to find the best combination of hyperparameters that maximizes the model's performance.

## Final Model

We train the final Random Forest model using the best hyperparameters obtained from the grid search.

## Evaluation

We evaluate the final model using metrics such as accuracy, precision, recall, and confusion matrix.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.



