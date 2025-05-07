# Random Forest Classification

This folder contains an implementation of a Random Forest classifier to predict health outcomes using the [`health_data.csv`](https://www.kaggle.com/datasets/akshatshaw7/cardiovascular-disease-dataset) dataset. The notebook explores ensemble learning concepts, feature importance, and compares performance with a single decision tree.

## Contents

- `random_forest.ipynb`: Jupyter Notebook implementing the Random Forest model using scikit-learn.
- `health_data.csv`: Dataset used for classification tasks.
- `diagram.png`: Illustration of the ensemble structure of a random forest (many decision trees combined).

## Overview

- **Random Forest**:
  - An ensemble method that builds multiple decision trees using bootstrapped data samples and feature randomness.
  - Each tree makes an independent prediction, and the final class is decided by majority vote (for classification).
  - Helps reduce overfitting and improves generalization.

- **Key Features**:
  - Handles both classification and regression
  - Provides feature importance scores
  - Robust against outliers and missing data

## How to Run

1. Clone this repo.
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
3. Open [`random_forest.ipynb`](./random_forest.ipynb) and run all cells.