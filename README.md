# Deep Learning and Neural Networks

## Companion Repository

This repository is a **study companion and practical implementation guide** for the book ***Deep Learning and Neural Networks***.

The goal of this project is to bridge the gap between **deep learning theory** and **hands-on neural network practice** by providing:

* Clear explanations of key deep learning concepts
* Step-by-step derivations and algorithm walkthroughs
* Python implementations from scratch
* Visualizations to build intuition for neural network behavior
* Original exercises with worked solutions

> 📌 **Important note**: This repository does **not** contain the book itself, nor does it reproduce copyrighted content. All explanations, code, and exercises are original and written as a learning aid.

---

## 🎯 Who This Repository Is For

This repo is designed for:

* Students learning **deep learning, AI, or machine learning**
* Practitioners who want to **strengthen neural network foundations**
* Engineers preparing for **deep learning-focused interviews**
* Researchers who want quick, runnable implementations of deep learning algorithms

If you have ever thought *“I know how to use frameworks like TensorFlow or PyTorch, but I want to understand what’s happening under the hood”*, this repository is for you.

---

## 🧠 Core Topics Covered

The repository follows a structure aligned with standard deep learning curricula:

* **Foundations of Neural Networks** (perceptron, MLPs, activation functions)
* **Backpropagation & Optimization** (gradient descent, loss functions, weight updates)
* **Regularization & Generalization** (dropout, L2/L1 regularization, early stopping)
* **Convolutional Neural Networks (CNNs)** (image processing, filters, pooling)
* **Recurrent Neural Networks (RNNs) & LSTMs** (sequence modeling, time series)
* **Autoencoders & Unsupervised Deep Learning**
* **Practical Deep Learning Pipelines** (data preprocessing, training loops, evaluation)

Each topic is treated with:

* Mathematical rigor
* Computational intuition
* Practical relevance for real-world datasets

---

## 📂 Repository Structure

```text
deep-learning-neural-networks/
│
├── README.md
├── LICENSE
├── requirements.txt
│
├── 01-neural-network-foundations/
│   ├── README.md
│   ├── perceptron.ipynb
│   ├── mlp_basics.ipynb
│   └── exercises.md
│
├── 02-backpropagation-optimization/
│   ├── gradient_descent.ipynb
│   ├── loss_functions.ipynb
│   └── weight_updates.ipynb
│
├── 03-regularization-generalization/
│   ├── dropout.ipynb
│   ├── l1_l2_regularization.ipynb
│   └── early_stopping.ipynb
│
├── 04-convolutional-neural-networks/
│   ├── cnn_basics.ipynb
│   ├── filters_pooling.ipynb
│   └── cnn_exercises.ipynb
│
├── 05-recurrent-neural-networks/
│   ├── rnn_basics.ipynb
│   ├── lstm.ipynb
│   └── sequence_modeling.ipynb
│
├── 06-autoencoders-unsupervised/
│   ├── autoencoder_basics.ipynb
│   └── variational_autoencoders.ipynb
│
├── 07-deep-learning-pipelines/
│   ├── preprocessing.ipynb
│   ├── training_loops.ipynb
│   └── evaluation.ipynb
│
└── utils/
    └── plotting.py
