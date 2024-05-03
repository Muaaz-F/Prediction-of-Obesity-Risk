# Obesity Classification Project

This project aims to classify individuals into different obesity levels based on various features such as age, gender, height, weight, and lifestyle factors. The classification is performed using machine learning algorithms, particularly Gradient Boosting, after thorough data preprocessing and hyperparameter optimization.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Overview](#overview)
4. [Summary of Work Done](#summary-of-work-done)
    - [Data Preprocessing](#data-preprocessing)
    - [Data Visualization](#data-visualization)
    - [Problem Formulation](#problem-formulation)
    - [Models Explored](#models-explored)
    - [Training](#training)
    - [Conclusions](#conclusions)
    - [Future Work](#future-work)
5. [Directory Structure](#directory-structure)
6. [Citations](#citations)

## Introduction

Obesity is a significant health concern globally, and its classification is crucial for personalized healthcare interventions. This project utilizes machine learning techniques to classify individuals into different obesity levels, aiding in early intervention and personalized treatment plans.

## Dataset

The dataset used in this project contains anonymized features such as age, gender, height, weight, and lifestyle factors (e.g., diet, physical activity) of individuals. Additionally, it includes the target variable indicating the multi obesity level. The dataset can be found [here](https://www.kaggle.com/competitions/playground-series-s4e2/data).

## Overview:

### Definition of the Task:
The task in this project is to classify individuals into different obesity levels based on various features such as age, gender, and lifestyle habits. The dataset includes anonymized information about individuals along with their corresponding obesity level.

### Approach:
Our approach formulates the problem as a classification task, where the goal is to predict the obesity level of individuals based on their features. We experimented with various machine learning algorithms such as Gradient Boosting and Voting Classifier. Additionally, feature selection techniques and ensemble modeling were employed to enhance the predictive performance.

### Summary of Performance Achieved:
Our best model achieved an accuracy of 0.9039 on the validation set. This means that the model accurately predicted the obesity level of individuals in the test data 90.39% of the time.

## Summary of Work Done

### Data Preprocessing

- **Encoding Categorical Variables:** Converted categorical variables into numerical format using techniques such as one-hot encoding or label encoding, depending on the nature of the data and the model requirements.
- **Feature Scaling:** Applied feature scaling techniques such as standardization or normalization to ensure all features have the same scale and prevent any particular feature from dominating the learning process.
- **Feature Engineering:** Created one new feature (derived feature) from existing ones to capture additional information that could be useful for the models.

### Data Visualization

- **Histograms of Numerical Features:** Visualized histograms of numerical features to understand their distributions and identify any patterns or anomalies.
- **Correlation Heatmap:** Generated a correlation heatmap to illustrate the pairwise correlations between different features in the dataset.

### Problem Formulation

- **Input / Output:** The input consists of various features such as age, gender, height, weight, family history of obesity, frequency of consumption of various types of food, physical activity, and other lifestyle-related factors. The output is the classification of individuals into one of seven weight categories based on their body mass index (BMI) and other features.

### Models Explored

| Model                        | Accuracy |
|------------------------------|----------|
| Random Forest Classifier     | 0.89     |
| Support Vector Machine (SVM) | 0.85     |
| Gradient Boosting Classifier | 0.90     |
| Decision Tree Classifier     | 0.83     |
| Ensemble Model 1             | 0.89     |
| **Ensemble Model 2**         | 0.91     |

### Training

Describe the training:
How you trained: Jupyter Notebook Local.
Need more computing power for Hyperparameter Optimization

### Conclusions

Ensemble Model 2 emerged as the top performer, achieving an accuracy of 91%. While Ensemble Model 2 showed a slight improvement in accuracy compared to other models, the difference may not be substantial. This suggests that further optimization or exploration of different model architectures and features might be necessary to achieve significant improvements in classification performance. Additionally, conducting more extensive hyperparameter tuning and feature engineering could potentially lead to better results.

### Future Work 

- **Next Steps:** Experiment with deep learning architectures such as neural networks to potentially improve model performance.
- **Further Studies:** Investigate the impact of additional features or alternative preprocessing techniques on classification accuracy.

## Directory Structure

- **data/**
  - `modified_train.csv`: CSV file containing preprocessed training data.
  - `modified_test.csv`: CSV file containing preprocessed test data.

- **notebooks/**
  - `Notebook_1.ipynb`: Notebook for initial data exploration, preprocessing and feature engineering.
  - `Notebook_2.ipynb`: Notebook for Models: RandomForestClassifier, SVM, GradientBoosting, DecisionTree.
  - `Notebook_3.ipynb`: Notebook for enseble models training using various algorithms and hyperparameter tuning.
  - `Notebook_4.ipynb`: Notebook for hyperparameter optimization with Gradient Boosting.


- **README.md**: Markdown file containing the overview, instructions, and documentation for the project.

## Citations

https://scikit-learn.org/stable/supervised_learning.html#supervised-learning
