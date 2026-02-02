# Project 3 – Image Classification (CIFAR-10) with a CNN

This project is part of the **Practical Deep Learning** course.

The goal of this assignment is to build, train, and evaluate a simple **Convolutional Neural Network (CNN)** for **CIFAR-10** image classification using **PyTorch**. The work includes dataset loading, train/validation split, batching with DataLoaders, CNN modeling, training, and testing.

---

## Tasks

### 3.1 – Dataset Initialization & Splitting
- Load the CIFAR-10 dataset using `torchvision`
- Keep the original test set
- Split the original training set into:
  - 45,000 samples for training
  - 5,000 samples for validation

### 3.2 – Dataset Sanity Checks & Batching
- Inspect sample images and labels
- Build DataLoaders for train/validation/test
- Iterate using mini-batches

### 3.3 – CNN Model Implementation
- Implement a custom CNN architecture in PyTorch
- Use convolutional layers, activation functions, and pooling
- Output logits for 10 classes

### 3.4 – Training & Evaluation
- Implement clean training and evaluation functions
- Train the CNN using the training set
- Evaluate on validation and test sets
- Report performance metrics (accuracy/loss)

---

## Dataset

- **CIFAR-10**: 60,000 RGB images (32×32), 10 classes  
- Default split:
  - 50,000 training images (further split into train/val)
  - 10,000 test images

---

## Environment

- Python 3
- PyTorch + torchvision
- NumPy, matplotlib

---

## Files

- `DL2025_proj3_Seyedehsahar_Fatemi_Abhari.ipynb` – full notebook solution (Parts 3.1–3.4)
