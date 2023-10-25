# Mobile Price Prediction Project

## Overview

This project aims to predict the prices of mobile phones using a Decision Tree model. The dataset used for this project contains various features related to mobile phones, such as specifications, features, and brand information. The project follows a structured data science workflow, including data preprocessing and feature selection, to build an accurate predictive model.

## Objectives

- Preprocess the dataset to handle missing values and outliers.
- Identify relevant features using statistical tests (Chi-square and ANOVA).
- Build a Decision Tree model to predict mobile phone prices.
- Evaluate the model's performance using appropriate metrics.
- Create visualizations to showcase the data and model results.

## Methodology

### Data Preprocessing

The dataset was subjected to thorough preprocessing to ensure the quality and integrity of the data. The following steps were taken:

- Handling Missing Values: Null values were identified and treated by either imputing missing data or removing rows with missing values.
- Outlier Detection and Treatment: Outliers were detected and managed to prevent them from negatively affecting the model.

### Feature Selection

Feature selection is a critical step in model building to improve prediction accuracy and reduce overfitting. Chi-square and ANOVA tests were performed to determine the statistical significance of each feature and select the most relevant ones based on their p-values.

### Model Building

A Decision Tree model was chosen for its ability to handle both categorical and numerical features. The model was trained on the selected features, and hyperparameters were tuned to achieve the best performance.

### Evaluation

The model's performance was evaluated using various evaluation metrics, such as accuracy, precision, recall, and F1-score. Cross-validation techniques were employed to ensure robustness and prevent overfitting.

### Visualizations

To provide a clear understanding of the dataset and model performance, visualizations were created. Graphs and charts were generated to illustrate the relationships between features and the model's prediction results.

## Results

The final Decision Tree model demonstrated promising predictive capabilities, with an accuracy of 83%. Visualizations provided insights into feature importance and the model's decision-making process.


