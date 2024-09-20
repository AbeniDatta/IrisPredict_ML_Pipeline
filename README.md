# Machine Learning Pipeline for the "load_iris" dataset available in the scikit-learn datasets module 

This repository contains a comprehensive machine learning pipeline built with Python, leveraging popular libraries such as scikit-learn and pandas. The pipeline demonstrates the full process of data loading, preprocessing, model training, evaluation, prediction and visualization using various classification algorithms.

## A little about the dataset used:

The Iris dataset is a classic dataset in machine learning, often used for classification tasks. It contains 150 samples of iris flowers, each with 4 features:
Sepal length, Sepal width, Petal length and Petal width.

These features are used to classify the flowers into 3 species: 
Setosa, Versicolor and Virginica.

The dataset is balanced, with 50 samples for each species. It’s included in the scikit-learn library and can be easily accessed using the load_iris() function.
The goal is typically to predict the species of an iris flower based on its features.

## Features:
1. Data Preprocessing: Implements feature scaling using StandardScaler to standardize data.
2. Model Selection: Supports multiple models - Logistic Regression and K-Nearest Neighbors (KNN). 
3. Voting Classifier: Combines multiple models using soft voting to improve classification accuracy.
4. Pipeline Structure: Uses scikit-learn’s Pipeline to streamline the process from data preparation to model evaluation.
5. Performance Metrics: Evaluates model performance using accuracy_score and other metrics.


## Visualizing Our Pipeline

<img width="662" alt="Screenshot 2024-09-19 at 11 31 23 PM" src="https://github.com/user-attachments/assets/cf07cc9d-6da7-45d7-8ea9-2986409bbd0a">

<img width="415" alt="Screenshot 2024-09-19 at 11 30 57 PM" src="https://github.com/user-attachments/assets/b2a89589-ed4b-46a3-9813-a21626a5540e">
