# Project 2 – Age Estimation with Facial Images (Feedforward Neural Networks)

This project is part of a Deep Learning (2025) course assignment.

The goal is to implement an age estimation model using facial images from the UTKFace dataset, and to understand how feedforward neural networks work by building key parts from scratch (NumPy-based forward/backprop), including training improvements such as momentum and basic tuning.

## Learning Objectives

- Understand the basics of (deep) feedforward neural networks
- Build a simple neural network from scratch using NumPy
- Implement forward propagation and backward propagation manually
- Use mean squared error (MSE) loss for age regression
- Apply mini-batch gradient descent with momentum
- Perform gradient checking using finite-difference approximation
- Tune hyperparameters and activation functions to improve performance

## Tasks

### Part 1 – Data loading and preprocessing
- Download UTKFace dataset (course-provided link)
- Preprocess training and test data
- Prepare input features and labels for regression (age)

### Part 2 – Neural network from scratch (NumPy)
- Check the structure of the dataset
- Initialize model parameters (weights and biases)
- Define activation functions
- Implement forward propagation
- Implement MSE loss
- Implement backward propagation (gradients for all parameters)
- Gradient checking (finite difference) to validate backprop

### Part 3 – Training and evaluation
- Train using mini-batches
- Use momentum to improve optimization stability
- Evaluate model performance on test data (regression quality)

### Part 4 – Activation function tuning
- Compare different activation functions
- Discuss the impact on training dynamics and performance

## Files

- DL2025_proj2_Seyedehsahar_Fatemi_Abhari.ipynb  
  Full implementation, experiments, and explanations.

## Environment

Suggested environment:
- Python 3
- NumPy
- PyTorch (>= 1.3)
- matplotlib
- Jupyter Notebook

You can run this locally, on CSC notebooks, or on Google Colab.

## Dataset (UTKFace)

UTKFace is not included in this repository.

To run the notebook:
1. Download UTKFace using the course-provided OneDrive link (or official source if allowed).
2. Place the dataset in the location expected by the notebook (or update the dataset path inside the notebook).
3. Run all cells from top to bottom.

## How to run

1. Open the notebook:
   DL2025_proj2_Seyedehsahar_Fatemi_Abhari.ipynb
2. Install any missing packages (if needed).
3. Run the notebook cells in order.
4. Verify results (training curves, evaluation output, and gradient check outputs).
5. ## Notebook Rendering Notice

GitHub may display the notebook as **"Invalid Notebook"** due to missing embedded attachments created during interactive execution.

The notebook is fully functional and can be viewed by:
- Downloading the `.ipynb` file
- Opening it locally in Jupyter Notebook or Google Colab

