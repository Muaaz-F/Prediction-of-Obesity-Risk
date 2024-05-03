# Obesity Classification Project

This project aims to classify individuals into different obesity levels based on various features such as age, gender, height, weight, and lifestyle factors. The classification is performed using machine learning algorithms, particularly Gradient Boosting, after thorough data preprocessing and hyperparameter optimization.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Overview](#overview)
4. [Usage](#usage)
5. [Results](#results)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction

Obesity is a significant health concern globally, and its classification is crucial for personalized healthcare interventions. This project utilizes machine learning techniques to classify individuals into different obesity levels, aiding in early intervention and personalized treatment plans.

## Dataset

The dataset used in this project contains anonymized features such as age, gender, height, weight, and lifestyle factors (e.g., diet, physical activity) of individuals. Additionally, it includes the target variable indicating the multi obesity level. The dataset can be found here https://www.kaggle.com/competitions/playground-series-s4e2/data


## Overview:

### Definition of the Task:
The task in this project is to classify individuals into different obesity levels based on various features such as age, gender, and lifestyle habits. The dataset includes anonymized information about individuals along with their corresponding obesity level.

### Approach:
Our approach formulates the problem as a classification task, where the goal is to predict the obesity level of individuals based on their features. We experimented with various machine learning algorithms such as Gradient Boosting and Voting Classifier. Additionally, feature selection techniques and ensemble modeling were employed to enhance the predictive performance.

### Summary of Performance Achieved:
Our best model achieved an accuracy of 0.9039 on the validation set. This means that the model accurately predicted the obesity level of individuals in the test data 90.39% of the time.


## Summary of the Work Done

### Data
Data: Obesity Risk <br />
Type: .csv <br />
Input: CSV file of features, output: 'NObeyesdad' in last column. <br />
Size: (20758, 18) <br />

### Preprocessing / Clean up

  * Encoding Categorical Variables:
    Converted categorical variables into numerical format using techniques such as one-hot encoding or label encoding, depending on the nature of the data and the model requirements.
  * Feature Scaling:
    Applied feature scaling techniques such as standardization or normalization to ensure all features have the same scale and prevent any particular feature from dominating the learning process.
  * Feature Engineering:
    Created one new feature (derived feature) from existing ones to capture additional information that could be useful for the models.

### Data Visualization <br />

    * Histograms of Numerical Features:
      Visualizing histograms of numerical features helps to understand their distributions and identify any patterns or anomalies. For example, we may observe that some features follow a normal distribution, while others exhibit skewness       or multimodality.
      
    * Correlation Heatmap:
      A correlation heatmap illustrates the pairwise correlations between different features in the dataset. This helps to identify strong correlations (positive or negative) between pairs of features, which can provide insights into           potential relationships and dependencies within the data.

