# Supervised Machine Learning Algorithms

This folder contains Jupyter Notebooks and datasets demonstrating eight core [supervised learning](https://www.ibm.com/think/topics/supervised-learning) algorithms, each applied to real-world datasets. These implementations include classification and regression tasks using models from linear to ensemble-based learners.

## Contents

| Algorithm               | Notebook                     | Dataset                      | Task Type     |
|------------------------|------------------------------|------------------------------|---------------|
| Perceptron             | `perceptron.ipynb`            | `Raisin_Dataset.csv`         | Classification |
| Linear Regression      | `linear_regression.ipynb`     | `possum.csv`                 | Regression    |
| Logistic Regression    | `logistic_regression.ipynb`   | `Pumpkin_Seeds_Dataset.xlsx` | Classification |
| Multilayer Perceptron  | `mlp.ipynb`                   | `CrabAgePrediction.csv`      | Regression    |
| K-Nearest Neighbors    | `k_nearest.ipynb`             | `citrus.csv`                 | Classification |
| Decision Tree          | `decision_tree.ipynb`         | `health_data.csv`            | Classification |
| Random Forest          | `random_forest.ipynb`         | `health_data.csv`            | Classification |
| Ensemble Methods       | `ensemble_methods.ipynb`      | `health_data.csv`            | Classification |

** note that some methods can be used for both classification and regression (Multilayer Perceptron, K-Nearest Neighbors, Decision Tree, Random Forest, and Ensemble Methods)

## Algorithms Overview

### 1. Perceptron
A single-layer binary classifier that updates weights based on misclassification using a step function.

### 2. Linear Regression
Fits a straight line to minimize squared error between predictions and targets using gradient descent and MSE loss.

### 3. Logistic Regression
Uses the sigmoid function to map linear combinations into probabilities for binary classification, trained using log loss.

### 4. Multilayer Perceptron (MLP)
A deep neural network with hidden layers and ReLU activation, used here for non-linear regression tasks.

### 5. K-Nearest Neighbors (KNN)
A non-parametric classifier that assigns class labels based on the majority class among the k closest data points.

### 6. Decision Tree
Recursively partitions the feature space based on entropy or Gini impurity to make decisions.

### 7. Random Forest
An ensemble of decision trees trained on random subsets of data and features, with majority voting to improve accuracy and reduce overfitting.

### 8. Ensemble Methods
Combines multiple models (e.g., Bagging, AdaBoost, Voting Classifier) to improve predictive performance through model aggregation.

## 📊 Metrics Used

- Accuracy
- Precision / Recall / F1-Score
- Confusion Matrix
- Mean Squared Error (for regression)
- R² Score (for regression)

## 🛠 How to Run

1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn tensorflow openpyxl
3. Open any notebook (.ipynb) and run all cells.
