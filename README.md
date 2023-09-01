# Chennai House Price Prediction

This repository contains code for a Chennai House Price Prediction project. The goal of this project is to predict house prices in Chennai using machine learning algorithms. The code is written in Python and uses various libraries for data preprocessing, model training, and evaluation.

## Table of Contents

1. [Introduction](#introduction)
2. [Dependencies](#dependencies)
3. [Data Loading](#data-loading)
4. [Data Preprocessing](#data-preprocessing)
5. [Exploratory Data Analysis](#exploratory-data-analysis)
6. [Model Building](#model-building)
7. [Model Evaluation](#model-evaluation)
8. [Conclusion](#conclusion)

## Introduction

The main objective of this project is to predict house prices in Chennai based on various features such as area, number of bedrooms, bathrooms, and more. The code includes data preprocessing, exploratory data analysis (EDA), and the training and evaluation of multiple machine learning models.

## Dependencies

Before running the code, make sure you have the following Python libraries installed:

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- xgboost

You can install these libraries using pip:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn xgboost
```

## Data Loading

The dataset used for this project is loaded from a CSV file named `train-chennai-sale.csv`. This file contains the data required for training and testing the machine learning models.

## Data Preprocessing

Data preprocessing includes tasks such as handling missing values, correcting spelling mistakes in categorical columns, converting data types, and more. The cleaned dataset is saved as `cleaned.csv` after preprocessing.

## Exploratory Data Analysis

EDA is performed to gain insights into the data. Visualizations and analyses are conducted to understand the relationships between various features and the target variable (house prices). Important insights and relationships are highlighted in the code.

## Model Building

Several machine learning algorithms are trained for house price prediction, including:

- Linear Regression
- K Nearest Neighbors (KNN)
- Decision Tree Regressor
- Random Forest Regressor
- XG Boost

Each model is trained and evaluated to determine its predictive performance.

## Model Evaluation

The performance of each model is evaluated using the R-squared (R2) score, which measures the goodness of fit. The README includes the R2 scores for each model, helping to identify the best-performing algorithm.

## Conclusion

The README concludes by stating that the XG Boost model is the best-performing algorithm for Chennai house price prediction, with an R2 score of 0.99.

Feel free to modify and use this code for your own projects or further analysis.

---

You can use this README as documentation for your code repository, providing a clear overview of the project, its dependencies, and the steps involved in data preprocessing, model building, and evaluation. It's essential for helping others understand and use your code effectively.
