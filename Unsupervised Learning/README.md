# Unsupervised Learning Algorithms

This folder contains implementations of several [unsupervised learning algorithms](https://www.ibm.com/think/topics/unsupervised-learning) using Jupyter notebooks. Each notebook explores a different method, using appropriate datasets and visualizations.

## Contents

| Algorithm                     | Notebook                   | Dataset Used         | Use Case                    |
|------------------------------|----------------------------|----------------------|-----------------------------|
| K-Means Clustering           | `k_means_clustering.ipynb` | `penguins.csv`       | Species clustering          |
| DBSCAN                       | `dbscan.ipynb`             | `penguins.csv`       | Density-based clustering    |
| PCA (Dimensionality Reduction) | `pca.ipynb`                | `Country-data.csv`   | Country feature compression |
| Image Compression w/ PCA     | `image_compression.ipynb`  | `dog.jpg`            | Image compression           |

## Algorithm Overview

### 1. **K-Means Clustering**
- **Description:** Partitions data into `k` clusters by minimizing intra-cluster variance.
- **Strengths:** Fast, intuitive, scalable.
- **Limitations:** Requires setting `k`; struggles with non-globular clusters.

### 2. **DBSCAN (Density-Based Spatial Clustering)**
- **Description:** Groups points that are closely packed, marking low-density points as outliers.
- **Strengths:** Finds clusters of arbitrary shapes, detects noise.
- **Limitations:** Sensitive to `eps` and `min_samples`.

### 3. **PCA (Principal Component Analysis)**
- **Description:** Reduces dimensionality while preserving variance, transforming features into orthogonal principal components.
- **Strengths:** Speeds up training, improves visualization, handles multicollinearity.
- **Limitations:** Hard to interpret transformed features.

### 4. **Image Compression with PCA**
- **Description:** Uses PCA to compress image data by reducing color channels.
- **Strengths:** Efficiently compresses images with minimal quality loss.
- **Limitations:** May lose fine details or color accuracy at high compression.

---

## Applications Table

| Algorithm                     | Dimensionality Reduction | Clustering |
|------------------------------|--------------------------|------------|
| K-Means Clustering           | ❌                       | ✅         |
| DBSCAN                       | ❌                       | ✅         |
| PCA                          | ✅                       | ❌         |
| Image Compression (PCA)      | ✅                       | ❌         |
