# Breast Cancer Classification Using Machine Learning

## Overview
This repository contains an implementation of various machine learning classification methods to recognize benign and malignant tumors based on the Breast Cancer Wisconsin (Diagnostic) dataset. The project compares the performance of eight different classification algorithms, both before and after feature extraction using Principal Component Analysis (PCA).

## Features
- **Dataset Preprocessing**
  - Correlation analysis and feature removal
  - Normalization and dataset splitting

- **Machine Learning Algorithms**
  - Multilayer Perceptron (MLP)
  - Naive Bayes
  - Logistic Regression
  - k-Nearest Neighbors (k-NN)
  - Support Vector Machine (SVM)
  - Decision Trees
  - Random Forest
  - AdaBoost

- **Performance Evaluation**
  - Comparison of classifiers using Mean Accuracy
  - Analysis of performance before and after PCA

## Dataset
The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) dataset, which can be obtained from [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data).

- **`Breast Cancer Wisconsin (Diagnostic) Data Set.csv`**: This file contains the dataset used for training and testing the machine learning models. It includes features extracted from medical images of breast tumors.

## Files
- **`breast-cancer-classification.ipynb`**: Jupyter Notebook containing the implementation and analysis.
- **`report.pdf`**: Project report detailing the methodology, results, and conclusions.
- **`Breast Cancer Wisconsin (Diagnostic) Data Set.csv`**: The dataset file used for the classification task.

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Python 3.6 or higher
- Libraries: numpy, pandas, scikit-learn, matplotlib, seaborn

You can install the required packages using the following command:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
