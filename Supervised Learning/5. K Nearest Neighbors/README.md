# K-Nearest Neighbors (KNN)

This folder contains an implementation of the K-Nearest Neighbors (KNN) algorithm applied to the [`citrus.csv`](https://www.kaggle.com/datasets/joshmcadams/oranges-vs-grapefruit) dataset. The model is used to classify citrus fruit samples based on their features.

## Contents

- `k_nearest.ipynb`: Jupyter Notebook implementing KNN classification and visual analysis.
- `citrus.csv`: Dataset used for training and testing.
- `knn_visualization.png`: Illustration of how KNN determines class membership using proximity.

## Overview

- **K-Nearest Neighbors (KNN)**:
  - A non-parametric, instance-based learning algorithm.
  - Makes predictions based on the majority class of the k-nearest training points.
  - Distance metrics (e.g. Euclidean) are used to determine "closeness."

- **Task**: Predict the class label of citrus fruits based on their measurements.

## How to Run

1. Clone this repo.
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
3. Open [`k_nearest.ipynb`](./k_nearest.ipynb) and run all cells.