# Heart Attack Risk Classification

A binary classification project that uses Logistic Regression to classify heart-attack risk based on clinical features.

## Project Overview

This project demonstrates a basic machine-learning workflow for binary classification:

- Data preprocessing and feature scaling with `StandardScaler`
- Model training with Logistic Regression
- Probability-based predictions and decision-threshold analysis
- Evaluation using accuracy and a confusion matrix

## Model

- **Algorithm:** Logistic Regression
- **Feature scaling:** `StandardScaler`
- **Regularization strength:** `C=0.01`
- **Solver:** `liblinear`
- **Default classification threshold:** `0.5`

## Results

At a probability threshold of `0.5`, the model achieved approximately **88.33% accuracy** on the test set.

Confusion matrix results:

| Metric | Count |
|---|---:|
| True Positives (TP) | 34 |
| True Negatives (TN) | 19 |
| False Positives (FP) | 4 |
| False Negatives (FN) | 3 |

The notebook also explores a threshold of `0.4`. Changing the threshold can affect the balance between false positives and false negatives, so the appropriate threshold depends on the use case.

## Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## How to Run

1. Clone the repository:
```bash
   git clone https://github.com/babakebrahimirafsanjani-cmyk/heart-attack-prediction.git
   
