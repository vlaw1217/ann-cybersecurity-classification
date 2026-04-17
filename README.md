# ANN Cybersecurity Classification

This project demonstrates an Artificial Neural Network (ANN) classification workflow using Python and scikit-learn. The goal is to predict security-related activity labels based on features such as login attempts, failed logins, session duration, transferred data, file access behavior, IP reputation score, and unusual access patterns.

## Project Overview

The notebook follows a complete machine learning pipeline:

1. Load the dataset
2. Check dataset information, missing values, and duplicates
3. Clean the data
4. Separate features and target label
5. Check class distribution
6. Split data into training and testing sets
7. Scale the features
8. Build an ANN model using `MLPClassifier`
9. Train the model
10. Make predictions
11. Evaluate model performance

## Tools and Libraries

- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook

## Model Used

The project uses an Artificial Neural Network classifier through scikit-learn's `MLPClassifier`.

## Evaluation

The model is evaluated using:

- Accuracy score
- Classification report
- Confusion matrix

These metrics help measure how well the model predicts the correct class labels.

## Files

- `TH_5_ANN.ipynb` — main Jupyter Notebook containing the full machine learning workflow
- `th5.csv` — dataset used for training and testing
- `.gitignore` — excludes unnecessary temporary files

## What I Learned

Through this project, I practiced:

- Preparing a dataset for machine learning
- Splitting data into training and testing sets
- Scaling numerical features
- Building and training an ANN classification model
- Evaluating classification performance using common metrics
- Organizing and publishing a machine learning project on GitHub
