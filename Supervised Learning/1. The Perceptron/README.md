# The Perceptron

This folder demonstrates the Perceptron classification algorithm using the [`Raisin_Dataset.csv`](https://www.kaggle.com/datasets/nimapourmoradi/raisin-binary-classification) dataset. The notebook explores how a basic linear classifier like the Perceptron performs on a two-class problem, including training process and decision boundary visualization.

## Contents

- `perceptron.ipynb`: Jupyter Notebook implementing the Perceptron algorithm.
- `Raisin_Dataset.csv`: Dataset used.

## Overview

- **Perceptron**:
  - A linear binary classifier that updates weights based on misclassifications.
  - Works best when data is linearly separable.
  - Sensitive to feature scaling and convergence depends on data distribution.

## How to Run

1. Clone this repo.
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn

3. Open [`perceptron.ipynb`](../1.%20The%20Perceptron/perceptron.ipynb) and run all cells.
