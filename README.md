# House Price Prediction Project

## Overview

This project aims to predict house sale prices based on various features using machine learning regression techniques. We explore a dataset containing 81 features that provide detailed descriptions of houses, moving beyond traditional metrics to identify what truly impacts price negotiations.

## Objectives

- **Data Analysis & Preprocessing**: Handle missing values, create new features, and select relevant features for modeling.
- **Model Training**: Experiment with various regression models to predict house prices, including:
  - Locally Weighted Linear Regression (LWLR)
  - K-Nearest Neighbors (KNN)
  - Decision Trees
  - Support Vector Machines (SVM)
- **Feature Reduction**: Use Principal Component Analysis (PCA) to reduce dimensionality and improve computational efficiency.
- **Model Evaluation**: Compare model accuracies through visual representation and utilize ensemble methods to combine model strengths.

## Dataset

The dataset used in this project contains 81 features that describe different properties of each house. Features include but are not limited to:

- Number of bedrooms
- Square footage
- Location attributes
- Structural details
- Condition ratings

### Missing Values

During preprocessing, some missing values were identified to have significance. These were addressed accordingly to enhance the dataset's integrity.

## Methodology

1. **Data Preprocessing**: Clean the dataset and create new features.
2. **Cross-Validation**: Split the data to ensure robust model training and evaluation.
3. **Feature Selection**: Identify the most relevant features using regularization techniques (Lasso, Ridge, ElasticNet).
4. **Model Training**: Train various regression models and tune hyperparameters such as learning rate and max iterations.
5. **Model Evaluation**: Assess the performance of each model and visualize results.
6. **Ensemble Techniques**: Combine multiple models to improve prediction accuracy.

## Installation

Clone this repository and install the necessary dependencies:

```bash
git clone https://github.com/zivshamli/House-Prices---Advanced-Regression-Techniques--ML--Assignment4.git
cd house-price-prediction
pip install -r requirements.txt
