# 🧠 Convolutional Neural Networks Lab Assignment

## 📌 Project Overview

This repository contains my complete implementation of a **CNN Laboratory Assignment**, covering the full deep learning pipeline — from data preprocessing to transfer learning.

The assignment is divided into **5 major tasks**, each focusing on different aspects of Convolutional Neural Networks.

---

## 🗂️ Tasks Breakdown

### 🔹 Task 1: Environment & Data Pipeline

* Setup deep learning environment
* GPU verification
* Dataset exploration (MNIST & CIFAR-10)
* Data preprocessing:

  * Normalisation
  * Reshaping
  * One-hot encoding
* Data augmentation pipeline

---

### 🔹 Task 2: CNN from Scratch

* Implemented **2D convolution using NumPy**
* Built **LeNet-5 architecture**
* Designed a **custom CNN for CIFAR-10**
* Calculated parameter counts manually

---

### 🔹 Task 3: Training & Regularisation

* Model training and evaluation
* Optimiser comparison:

  * SGD
  * SGD + Momentum
  * Adam
* Hyperparameter tuning (LR & Batch Size)
* Regularisation techniques:

  * Dropout
  * Batch Normalisation
* Learning rate scheduling

---

### 🔹 Task 4: Visualisation & Interpretability

* Visualised convolution filters
* Extracted feature maps from different layers
* Implemented **Grad-CAM from scratch**
* Generated:

  * Confusion matrix
  * Classification report

---

### 🔹 Task 5: Transfer Learning

* Used pre-trained models (VGG16 / ResNet50)
* Feature extraction with frozen base
* Fine-tuning with gradual unfreezing
* Ablation study on trainable layers
* Compared:

  * Training from scratch vs Transfer learning

---

## ⚙️ Installation & Setup

```bash
pip install -r requirements.txt
```

Required libraries:

* TensorFlow / PyTorch
* NumPy
* Matplotlib
* Pandas
* scikit-learn
* seaborn

---

## ▶️ How to Run

1. Open Jupyter Notebook / Google Colab
2. Run all cells sequentially
3. Ensure GPU is enabled (optional but recommended)

---

## ✅ Key Learnings

* Understanding CNN architecture deeply
* Manual implementation of convolution
* Importance of hyperparameter tuning
* Regularisation to prevent overfitting
* Model interpretability using Grad-CAM
* Practical use of transfer learning

---

## ⭐ Acknowledgement

This assignment was completed as part of the coursework to gain hands-on experience with **Convolutional Neural Networks** and real-world deep learning workflows.

---
