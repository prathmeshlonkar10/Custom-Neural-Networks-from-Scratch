# 🧠 Neural Network from Scratch — Logistic Regression with Custom Gradient Descent

This project implements a **single-neuron Neural Network (similar to logistic regression)** completely from scratch using NumPy, and then compares it with TensorFlow's implementation to verify correctness and performance. The goal is to deeply understand forward propagation, loss calculation, backpropagation, and gradient descent by hand-coding everything without relying on high-level libraries.

## Snippet of Explanation

![neuron](assets/neuron.jpg)

---

## 📚 Overview

In this notebook, you'll find:

- Manual implementation of a neural network with 1 neuron (i.e., logistic regression)
- Custom forward pass using the sigmoid activation
- Custom backpropagation using binary cross-entropy loss
- Gradient descent to update weights and bias
- Training loop with accuracy and loss tracking
- Visual comparison of predictions from custom model vs. TensorFlow model
- 3D plot of predicted probabilities based on input features
