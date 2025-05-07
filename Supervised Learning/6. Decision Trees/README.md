# Decision Tree Classifier

This folder contains a decision tree implementation to classify health outcomes using the [`health_data.csv`](https://www.kaggle.com/datasets/akshatshaw7/cardiovascular-disease-dataset) dataset. The notebook explains core concepts like entropy and information gain, and visualizes how decision trees split data.

## Contents

- `decision_tree.ipynb`: Jupyter Notebook implementing decision tree classification.
- `health_data.csv`: Dataset used for training and evaluation.
- `entropy_formula.png`: Image showing the entropy formula used in information gain.
- `decision_tree_diagram.png`: Diagram illustrating a basic decision tree structure.

## Overview

- **Decision Tree**:
  - A supervised learning model that splits data at nodes based on features to reduce impurity.
  - Splits are evaluated using entropy:
    \[
    \text{Entropy}(S) = - \sum_{c \in C} p(c) \log_2 p(c)
    \]
  - Uses information gain to determine the best attribute to split on.

- **Task**: Predict a binary health outcome based on individual attributes.

## How to Run

1. Clone this repo.
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
3. Open [`decision_tree.ipynb`](./decision_tree.ipynb) and run all cells.