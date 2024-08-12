# Predicting Heart Attacks through Analysis of Features

## Project Overview
This project utilizes machine learning models to predict heart attack occurrences. The models were built and trained using a dataset containing health-related features and an output variable signifying whether an individual has suffered a heart attack.

## Models
Three decision tree models were developed:

1. A model with all provided features.
2. A model with the 5 highest correlated features.
3. A model with 2 highly predictive features.

## Data
The dataset used in this project is public and updated regularly. It was collected via a crawler from a reputable source and features abundant, well-documented data points. Each row in the dataset represents an individual and contains  health-related features and an output variable that represents if the individual has suffered a heart attack. The features include age, gender, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, resting electrocardiograph results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise, slope of the peak exercise ST segment, number of major vessels, and Thallium Stress Test result.

## Analysis
A basic feature analysis was conducted to identify health factors often associated with heart attacks, such as older age, higher maximum heart rates, and higher cholesterol levels. The findings were visualized using the Gaussian Kernel Density Estimate (KDE) to analyze the probability distribution for each feature.

Following the initial analysis, decision tree models were trained to predict heart attack occurrences. The models' performances were evaluated using accuracy, mean square error, precision, recall, and f-score metrics.

## Findings
The findings of the project were mixed. The basic feature analysis revealed weak correlations between age and likelihood of heart attacks and no clear connection between cholesterol levels and heart attack likelihood. However, a higher maximum heart rate was found to be a significant factor in heart attack likelihood.

The decision tree models performed with varying levels of success. The model utilizing all features expectedly had the highest accuracy, while the model using only sex and chest pain as features was only marginally less accurate.

## Future Work
Future work includes the creation of additional machine learning models to predict heart attack occurrences with an accuracy of >95%, the development of more decision tree models to determine other pairs of features that can predict heart attacks with high accuracy, and the exploration of other machine learning models such as k-nearest models and various boosting algorithms.
