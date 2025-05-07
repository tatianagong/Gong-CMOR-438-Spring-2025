# Multilayer Perceptron (MLP)

This folder contains an implementation of a Multilayer Perceptron (MLP) neural network for predicting crab ages using the [`CrabAgePrediction.csv`](https://www.kaggle.com/datasets/sidhus/crab-age-prediction) dataset. The notebook applies a feedforward neural network to a regression task.

## Contents

- `mlp.ipynb`: Jupyter Notebook implementing a deep neural network using TensorFlow/Keras.
- `CrabAgePrediction.csv`: Dataset used for training and evaluation.

## Overview

- **Multilayer Perceptron (MLP)**:
  - A deep neural network composed of fully connected layers.
  - Uses ReLU activation in hidden layers and a linear output for regression.
  - Optimized with Mean Squared Error (MSE) loss.

- **Task**: Predict crab age based on physical and biological measurements.

## How to Run

1. Clone this repo.
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
3. Open [`mlp.ipynb`](./mlp.ipynb)and run all cells.
