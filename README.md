# Deep Learning Projects

This repository contains my coursework projects for the **Practical Deep Learning** course at the **University of Oulu**.

The projects cover core deep learning concepts using **PyTorch**, including linear models, feedforward neural networks, convolutional neural networks, and recurrent neural networks.  
Each project focuses on a different model family, dataset, and learning objective.

> **Note:** The final course project (Multi-label Retinal Disease Detection with Transfer Learning) is maintained in a **separate repository** due to its size and research scope.

---

## Projects Overview

### Project 1 – Breast Cancer Classification (Logistic Regression)
**Topic:** Binary classification with linear models  
**Dataset:** Breast Cancer Wisconsin (Diagnostic)  
**Key Concepts:**
- Train/test data splitting
- Logistic regression from scratch in PyTorch
- Binary cross-entropy loss
- Training dynamics and visualization

**Tech:** PyTorch, NumPy, scikit-learn

📁 `Project-1-Breast-Cancer-Classification`

---

### Project 2 – Age Estimation with Feedforward Neural Networks
**Topic:** Regression with neural networks  
**Dataset:** UTKFace  
**Key Concepts:**
- Feedforward neural networks (from scratch with NumPy)
- Backpropagation and gradient checking
- Mini-batch gradient descent with momentum
- Hyperparameter and activation tuning

**Tech:** NumPy, PyTorch, matplotlib

📁 `Project-2-Age-Estimation-Feedforward-NN`

---

### Project 3 – Image Classification with CNNs (CIFAR-10)
**Topic:** Convolutional Neural Networks  
**Dataset:** CIFAR-10  
**Key Concepts:**
- Custom PyTorch datasets
- Train/validation/test splits
- CNN architecture design
- Training and evaluation pipelines

**Tech:** PyTorch, torchvision, NumPy, matplotlib

📁 `Project-3-CIFAR10-Image-Classification-CNN`

---

### Project 4 – Emojify with RNN / LSTM
**Topic:** Sequence modeling and word embeddings  
**Dataset:** Emojify sentence dataset  
**Key Concepts:**
- Recurrent Neural Networks (RNNs)
- LSTM networks
- One-hot word representations
- Pre-trained **GloVe** embeddings
- Text classification and generalization to unseen sentences

**Tech:** PyTorch, NumPy, emoji, matplotlib

📁 `Project-4-Emojify-LSTM-Glove`

---

## Environment

- Python 3
- PyTorch (≥ 1.3)
- NumPy, matplotlib
- torchvision (for image datasets)

Projects were developed and tested using:
- **CSC Notebooks**
- **Google Colab**
- Local Jupyter environments

---

## Notes

- Datasets and large pretrained files (e.g., GloVe vectors) are **not included** in this repository.
- Each project folder contains a dedicated `README.md` explaining:
  - task objectives
  - implementation details
  - how to run the code

---

## Final Project

The final project **“Multi-label Retinal Disease Detection with Transfer Learning (ODIR)”**  
is maintained in a **separate repository** due to its research-level scope, trained models, and report requirements.
