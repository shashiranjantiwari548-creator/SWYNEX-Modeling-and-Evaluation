# SWYNEX Modeling and Evaluation

## Project Overview
This project builds and evaluates baseline machine learning models using the Netflix Titles dataset.

## Objectives
- Prepare features and target variables.
- Split the dataset into training and testing sets.
- Train a Dummy Classifier and Logistic Regression model.
- Evaluate models using accuracy, precision, recall, and F1-score.
- Visualize model performance and discuss limitations.

## Models
- Dummy Classifier
- Logistic Regression with genre
- Logistic Regression without genre

## Results

| Model | Accuracy | Macro F1 |
|---|---:|---:|
| Dummy Classifier | 69.64% | 0.4105 |
| Logistic Regression (with genre) | 100.00% | 1.0000 |
| Logistic Regression (without genre) | 74.46% | 0.6582 |

The perfect score with genre should be interpreted cautiously because genre is strongly associated with content type.

## Limitations
- The dataset represents a Netflix catalogue snapshot.
- The dataset has more Movies than TV Shows.
- Only one stratified train-test split was used.
- Cross-validation and external validation have not been performed.
- The model is an educational baseline, not a production-ready system.

## Tools and Libraries
Python, Pandas, NumPy, Matplotlib, and Scikit-learn.

## Notebook
See `modeling_evaluation.ipynb` for the model development and evaluation notebook.
