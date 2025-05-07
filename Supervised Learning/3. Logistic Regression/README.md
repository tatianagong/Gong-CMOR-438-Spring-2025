# Logistic Regression

This folder contains an implementation of logistic regression applied to the [`Pumpkin_Seeds_Dataset.xlsx`](https://www.kaggle.com/datasets/muratkokludataset/pumpkin-seeds-dataset) dataset. The model is used to classify different types of pumpkin seeds based on their geometric features.

## Contents

- `logistic_regression.ipynb`: Jupyter Notebook implementing logistic regression from scratch and using scikit-learn.
- `Pumpkin_Seeds_Dataset.xlsx`: Dataset used for training and testing.

## Overview

- **Logistic Regression**:
  - A linear model used for binary or multiclass classification.
  - Applies the sigmoid activation to convert linear output into a probability:
    \[
    \hat{y} = \frac{1}{1 + e^{-(w^Tx + b)}}
    \]
  - Trained using cross-entropy loss for classification tasks.

## How to Run

1. Clone this repo.
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn openpyxl
3. Open [`logistic_regression.ipynb`](./logistic_regression.ipynb) and run all cells.
