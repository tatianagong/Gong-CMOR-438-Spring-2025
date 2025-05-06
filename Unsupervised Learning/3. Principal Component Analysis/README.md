# Principal Component Analysis (PCA)

This folder explores Principal Component Analysis (PCA), a dimensionality reduction technique that identifies the directions (principal components) capturing the most variance in a dataset. PCA is implemented here using country-level economic and social indicators.

## Contents

- `pca.ipynb` — Jupyter Notebook containing code, plots, and explanations.
- [Country-data.csv](https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data) — Dataset containing numeric features for various countries.
- `pca_visualization.png` — PCA diagram illustrating how PCA reorients data axes.

## PCA Overview

PCA transforms correlated variables into a smaller set of uncorrelated components, making it easier to visualize and analyze high-dimensional data. It leverages **Singular Value Decomposition (SVD)** to identify directions of maximum variance.

### Visualizations

- **Pairplot with KDEs** — Displays feature relationships and distributions.
- **Covariance Heatmap** — Reveals inter-feature correlations.
- **Explained Variance Plot** — Shows how much variance each principal component retains.
- **Loading Scores** — Highlights which original features contribute most to PC1 and PC2.
- **PCA Scatterplot (PC1 vs. PC2)** — Visualizes country clustering in reduced dimensions.

## Key Takeaways

- The first two principal components captured the majority of the variance.
- Strong feature groupings (e.g., GDP, income, life expectancy) contribute most to PC1.
- PCA helps simplify the structure of the dataset for visualization and potential downstream tasks like clustering or classification.

## How to Run

1. Clone this repo.
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
3. Open `pca.ipynb` and run all cells.
