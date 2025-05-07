# Ensemble Methods for Health Outcome Prediction

This folder contains implementations of various ensemble learning techniques to predict health outcomes using the [`health_data.csv`](https://www.kaggle.com/datasets/akshatshaw7/cardiovascular-disease-dataset) dataset. The notebook explores and compares multiple models including bagging, boosting, and voting classifiers.

## Contents

- `ensemble_methods.ipynb`: Jupyter Notebook implementing and comparing ensemble techniques.
- `health_data.csv`: Dataset containing patient features and health labels.

## Models Implemented

- **Bagging Classifier**: Builds multiple base learners (typically decision trees) on bootstrapped subsets and averages their predictions.
- **Random Forest**: An improved bagging method that also adds feature randomness to reduce correlation between trees.
- **AdaBoost**: A boosting method that sequentially trains weak learners by focusing more on misclassified samples.

## How to Run

1. Clone this repo.
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
3. Open [`ensemble_methods.ipynb`](./ensemble_methods.ipynb) and run all cells.
