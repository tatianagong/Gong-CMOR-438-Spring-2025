# Density_Based Spatial Clustering of Applications with Noise (DBSCAN)

This folder compares DBSCAN (Density-Based Spatial Clustering of Applications with Noise) and K-Means, two popular clustering algorithms in unsupervised machine learning. Through visualizations, simulations, and real dataset applications, we demonstrate the advantages and limitations of each technique.

##  Overview

### K-Means
- Requires the number of clusters to be defined beforehand.
- Assumes clusters are spherical/convex.
- Sensitive to outliers and noise.
- Uses only 1 hyperparameter (number of clusters `k`).

### DBSCAN
- No need to specify the number of clusters.
- Capable of detecting arbitrarily shaped clusters.
- Performs well in presence of noise and outliers.
- Requires 2 parameters: `eps` (radius) and `min_samples`.

## Contents

- `dbscan.ipynb` - Main notebook demonstrating DBSCAN and K-Means on [penguin.csv](https://www.kaggle.com/datasets/youssefaboelwafa/clustering-penguins-species).
- `penguins.csv` - Dataset used to apply clustering to real-world biological data.
- `comparison_table.png` - Visual table summarizing key differences between DBSCAN and K-Means.
- `db_vs_kmeans.jpeg` - Comparison of clustering results on non-linear datasets
- `dbscan_algorithm.jpeg` - Visual explanation of DBSCAN core, border, and noise points.


## How to Run

1. Clone this repo.
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
3. Open `dbscan.ipynb` and run all cells.