# Project 1 – Breast Cancer Classification (Logistic Regression in PyTorch)

This project is part of the Deep Learning course.

The goal is to build a simple binary classifier for the Breast Cancer Wisconsin (Diagnostic) dataset using logistic regression, implemented in PyTorch (without using torch.nn.Linear for the main model).

---

## Learning Goals

- Load a dataset and create a train/test split
- Implement logistic regression (linear classification) in PyTorch
- Train a model using binary cross entropy loss
- Visualize training behavior (loss curve)
- Compare with a baseline Scikit-learn logistic regression model

---

## Dataset

Breast Cancer Wisconsin (Diagnostic) dataset (sklearn.datasets.load_breast_cancer)

- 569 samples
- 30 numerical features
- Binary labels: benign vs malignant

---

## What I Implemented

### Part 1 – Data Loading and Split

- Loaded the dataset from scikit-learn
- Split into training and testing sets using train_test_split
- Converted arrays into PyTorch tensors (features and labels)

### Part 2 – Logistic Regression

#### Part 2.0 – Baseline (Scikit-learn)

- Trained LogisticRegression from scikit-learn as a reference
- Test accuracy: 0.9825

#### Part 2.1 – PyTorch Model

- Implemented a custom linear layer (weights + bias) and forward pass
- Implemented a sigmoid activation function
- Built a logistic regression model using these components

#### Part 2.2 – Training

- Used binary cross entropy loss
- Performed gradient-based optimization (manual update step)
- Tracked loss over epochs
- Evaluated performance on the test set

PyTorch test accuracy: 0.9649

---

## Results Summary

- Scikit-learn Logistic Regression accuracy: 0.9825
- PyTorch Logistic Regression accuracy: 0.9649

The baseline performs slightly better, which is expected because scikit-learn uses well-tested solvers and regularization defaults. The PyTorch implementation shows the full training pipeline clearly and achieves strong performance.

---

## Files

- `DL2025_Proj1_Seyedehsahar_Fatemi_Abhari.ipynb` – Full implementation and results

---

## How to Run

1. Open the notebook in Jupyter or Google Colab
2. Install dependencies if needed
3. Run all cells from top to bottom

---

## Environment

- Python 3
- PyTorch
- scikit-learn
- numpy
- pandas
- matplotlib
