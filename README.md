# 🌸 Iris Classification using Random Forest

A classic classification project using the Iris dataset, demonstrating the full ML workflow from data loading to model evaluation and feature importance analysis.

## 📌 Overview

This project builds a **Random Forest classifier** on the well-known Iris dataset. The focus extends beyond accuracy to **model interpretability** - understanding which features drive predictions, a critical skill when presenting findings to BI and analyst teams.

## 🗂️ Dataset

- **Source:** `sklearn.datasets.load_iris` (built-in)
- **Samples:** 150 (50 per class)
- **Features:** Sepal length, Sepal width, Petal length, Petal width
- **Classes:** Setosa, Versicolor, Virginica

## 🔍 What This Project Covers

- Loading and inspecting the Iris dataset
- Splitting data into training and test sets
- Training a Random Forest classifier
- Evaluating model performance (accuracy, confusion matrix)
- Analysing **feature importance** for model interpretability

## 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| scikit-learn | Random Forest, train/test split, evaluation |
| Pandas / NumPy | Data handling |
| Matplotlib | Visualisation |

## 📈 Results

The Random Forest classifier achieves **high predictive accuracy** on the Iris test set, with petal dimensions identified as the most informative features.

## 🚀 How to Run

```bash
git clone https://github.com/MbongeniThwala-projects/iris-classification.git
cd iris-classification

pip install scikit-learn pandas numpy matplotlib

jupyter notebook Classification_Model_for_Iris_dataset.ipynb
```

## 💡 Key Learnings

- Random Forests are robust, low-tuning classifiers that provide built-in feature importance
- Feature importance scores are a practical tool for communicating model behaviour to non-technical stakeholders
