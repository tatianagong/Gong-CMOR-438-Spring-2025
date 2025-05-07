# Gong-CMOR-438-Spring-2025  
## CMOR 438 / INDE 577: Data Science & Machine Learning  
This repository houses various concepts and algorithms taught during the Spring 2025 semester at Rice University. It includes both supervised and unsupervised machine learning methods implemented using Jupyter Notebooks, complete with visualizations and real-world datasets.

## Contents

### Supervised Learning

| Algorithm              | Description                                        | Task Type               |
|------------------------|----------------------------------------------------|--------------------------|
| Perceptron             | Basic linear binary classifier                     | Binary Classification    |
| Linear Regression      | Predicts continuous values using a linear model    | Regression               |
| Logistic Regression    | Linear model using sigmoid for classification      | Binary Classification    |
| Neural Network (MLP)   | Multi-layer perceptron using backpropagation       | Regression               |
| K-Nearest Neighbors    | Classifies based on nearest data points            | Binary Classification    |
| Decision Tree          | Recursive tree-based decision model                | Both                     |
| Random Forest          | Ensemble of decision trees                         | Both                     |
| Ensemble Methods       | Combines predictions from multiple models          | Both                     |

📁 Folder: `Supervised_Algorithms/`  
Each algorithm is documented with Markdown cells, visual outputs, and performance evaluations.

### Unsupervised Learning

| Algorithm                     | Description                                      | Task Type               |
|------------------------------|--------------------------------------------------|--------------------------|
| K-Means Clustering           | Partitions data into `k` clusters                | Clustering               |
| DBSCAN                       | Density-based clustering algorithm               | Clustering               |
| PCA                          | Dimensionality reduction using variance capture | Dimensionality Reduction |
| Image Compression with PCA   | Applies PCA to compress image data               | Dimensionality Reduction |

📁 Folder: `Unsupervised_Algorithms/`  
Notebooks explore exploratory data analysis, clustering visualization, and compression.

## Summary Table

| Algorithm           | Classification | Regression | Clustering | Dim. Reduction |
|--------------------|----------------|------------|------------|----------------|
| Perceptron         | ✅             | ❌         | ❌         | ❌             |
| Linear Regression  | ❌             | ✅         | ❌         | ❌             |
| Logistic Regression| ✅             | ❌         | ❌         | ❌             |
| Neural Network     | ✅ / ✅         | ✅         | ❌         | ❌             |
| KNN                | ✅             | ✅         | ❌         | ❌             |
| Decision Tree      | ✅             | ✅         | ❌         | ❌             |
| Random Forest      | ✅             | ✅         | ❌         | ❌             |
| Ensemble Methods   | ✅             | ✅         | ❌         | ❌             |
| K-Means Clustering | ❌             | ❌         | ✅         | ❌             |
| DBSCAN             | ❌             | ❌         | ✅         | ❌             |
| PCA                | ❌             | ❌         | ❌         | ✅             |
| Image Compression  | ❌             | ❌         | ❌         | ✅             |

## Author
**Tatiana T. Gong**  
Spring 2025 · Rice University · CMOR 438 / INDE 577

## Requirements
- Python 3.10+
- `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `tensorflow` (for MLP)

## 🗂️ License
This project is for educational purposes only under Rice University's Spring 2025 Data Science curriculum.
