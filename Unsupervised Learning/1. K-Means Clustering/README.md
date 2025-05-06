# K-Means Clustering

This folder demonstrates the K-Means clustering technique using the [`penguins.csv`](https://www.kaggle.com/datasets/youssefaboelwafa/clustering-penguins-species) dataset. Visuals and behavior of both algorithms are explored, highlighting how they handle outliers, shape of clusters, and parameter requirements.

## Contents

- `k_means_clustering.ipynb`: Jupyter Notebook implementing K-Means.
- `penguins.csv`: Dataset used.

## Overview

- **K-Means**:
  - Partitions data into `k` spherical clusters.
  - Sensitive to outliers.
  - Requires specification of `k` (number of clusters).

## How to Run

1. Clone this repo.
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
3. Open `k_means_clustering.ipynb` and run all cells.