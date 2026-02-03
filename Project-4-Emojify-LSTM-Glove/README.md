# Project 4 – Emojify with Recurrent Neural Networks (RNN/LSTM)

This project is part of the **Practical Deep Learning** course.

The goal of this project is to implement an **Emojify** model that predicts an emoji label from a short input sentence using **PyTorch**, first with **one-hot word vectors**, and then with **pre-trained GloVe word embeddings**.

---

## Tasks

### Part 1 – Setup and Data Download
- Import required libraries and check CUDA availability.
- Download/load the Emojify dataset and the **GloVe** word embeddings.

### Part 2 – Model Construction
- Implement the LSTM-based model and its **forward propagation**.
- Build a **one-hot** input pipeline (tokenization + vocabulary + vectorization).
- Build a **GloVe embedding layer** and use it as the model input.

### Part 3 – Training and Evaluation
- Train the model using a loss function and optimizer.
- Evaluate performance using accuracy and loss curves on the test set.

### Part 4 – Emojify on Custom Sentences
- Test the trained model on custom sentences to verify generalization to unseen words.

---

## Files

- `DL2025_Project4_Emojify_LSTM_GloVe.ipynb` – Full implementation for Parts 1–4

---

## Notes on Data
The dataset and GloVe embeddings are **not included in this repository** (course-provided / downloaded inside the notebook).
The notebook contains the download/loading steps and can be executed in **CSC Notebooks** or **Google Colab**.

---

## How to Run
1. Open the notebook in **Google Colab** or **Jupyter**.
2. Run cells in order from top to bottom.
3. If using GPU, enable it in Colab:  
   **Runtime → Change runtime type → GPU**
