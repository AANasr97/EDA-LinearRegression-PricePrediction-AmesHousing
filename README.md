# EDA | Price Prediction | Ames Housing

## Table of Contents
1. [Introduction](#introduction)
2. [Imports](#imports)
3. [Ames Data Set](#ames-data-set)
4. [Dealing with Outliers](#dealing-with-outliers)
   - Visualizing and Describing the Data
   - Handling Outliers
   - Trimming or Fixing Based on Domain Knowledge
5. [Dealing with Missing Data](#dealing-with-missing-data)
   - Handling Missing Data
   - Working based on Rows Missing Data
   - Working based on Columns Missing Data
6. [Dealing with Categorical Data](#dealing-with-categorical-data)
   - Creating Dummy Variables
7. [Simple Linear Regression](#simple-linear-regression)
   - Data Preparation
   - Training the Model
   - Model Evaluation
   - OLS Regression
8. [Polynomial Regression](#polynomial-regression)
   - Data Transformation
   - Model Training
   - Model Evaluation
9. [Regularization](#regularization)
   - L2 Ridge Regression
   - Choosing an Alpha Value with Cross-Validation
   - L1 Lasso Regression
   - Elastic Net

## Introduction
This repository contains code and analysis for exploratory data analysis (EDA), price prediction, and data analysis on the Ames Housing dataset. The code covers data preprocessing, handling outliers, dealing with missing data, and various regression techniques, including simple linear regression, polynomial regression, and regularization techniques like Ridge, Lasso, and Elastic Net.

## Imports
The required Python libraries are imported in this section, including NumPy, Pandas, Matplotlib, Seaborn, Statsmodels, and more.

## Ames Data Set
The code loads the Ames Housing dataset and provides an initial overview of the data.

## Dealing with Outliers
This section focuses on identifying and handling outliers in the data, visualizing outliers using scatterplots and histograms, and removing or adjusting outliers based on domain knowledge.

## Dealing with Missing Data
The code addresses missing data in the dataset by identifying columns with missing values, analyzing the percentage of missing data, and filling or dropping missing values accordingly.

## Dealing with Categorical Data
Categorical data is handled by creating dummy variables to convert them into a format suitable for regression analysis.

## Simple Linear Regression
The code explores simple linear regression, including data preparation, model training, model evaluation, and ordinary least squares (OLS) regression analysis.

## Polynomial Regression
This section covers polynomial regression, transforming the data for polynomial features, training polynomial regression models, and evaluating them.

## Regularization
Regularization techniques like Ridge, Lasso, and Elastic Net are applied to the data to improve model performance and prevent overfitting. Cross-validation is used to select the best alpha values for regularization.

Feel free to explore each section of the code for a detailed analysis of the Ames Housing dataset and the various regression techniques applied.
