# XG_Boost

This repository contains a machine learning notebook for building and evaluating a Gradient Boosting Machine (GBM) classifier on the Breast Cancer Wisconsin dataset.

## Project Overview
The notebook demonstrates:
- loading the breast cancer dataset
- understanding the data
- checking for missing values and dtypes
- preparing features and target variables
- scaling features
- splitting data into train/test sets
- training a classifier
- evaluating model performance

## Dataset
The dataset used is the scikit-learn `load_breast_cancer()` dataset, which contains features describing cell nuclei measurements and a target label indicating whether the tumor is malignant or benign.

## Workflow
The notebook performs the following steps:
1. Import necessary libraries
2. Load and inspect the dataset
3. Check for missing values and data types
4. Separate features (`X`) from target (`y`)
5. Scale the feature values
6. Split the dataset into training and testing sets
7. Train the model
8. Evaluate using:
   - confusion matrix
   - accuracy score
   - precision score
   - recall score

## Dependencies
Install the required libraries using:

```bash
pip install pandas scikit-learn
