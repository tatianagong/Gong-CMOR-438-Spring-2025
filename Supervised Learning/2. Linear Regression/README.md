# Linear Regression with a Single Neuron

This folder contains a simple implementation of linear regression using a single artificial neuron. The model is trained on the [`possum.csv`](https://www.kaggle.com/datasets/abrambeyer/openintro-possum) dataset to predict continuous values using gradient descent.

## Contents

- `linear_regression.ipynb`: Jupyter Notebook implementing linear regression using a basic neuron architecture.
- `possum.csv`: Dataset used.
- `neuron.png`: Diagram of the neuron model used.
- `equation.png`: Visualization of the cost function.

## Overview

- **Linear Neuron**:
  - Computes the output as \( z = w_1 x + b \)
  - Uses an identity activation function \( \phi(z) = z \)
  - Optimized using Mean Squared Error (MSE) loss:
    \[
    C(w, b) = \frac{1}{2N} \sum_{i=1}^N \left( \hat{y}^{(i)} - y^{(i)} \right)^2
    \]

## How to Run

1. Clone this repo.
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
3. Open [`linear_regression.ipynb`](./linear_regression.ipynb) and run all cells.