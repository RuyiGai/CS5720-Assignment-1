# CS5720 Neural Network and Deep Learning - Home Assignment 1

## Student Information

- **Name:** Ruyi Gai
- **Course:** CS5720 Neural Network and Deep Learning
- **Semester:** Fall 2026
- **University:** University of Central Missouri
- **Department:** Department of Computer Science & Cybersecurity

---

## Assignment Overview

This assignment covers fundamental concepts of neural networks and several TensorFlow programming tasks. The programming part includes tensor manipulation, loss function comparison, optimizer comparison, and TensorBoard visualization.

The source code is provided in the Jupyter Notebook:

`Assignment 1.ipynb`

---

# Part I. Short Answer

Part I covers the following neural network concepts:

- Traditional Programming vs. Machine Learning
- Artificial Intelligence, Machine Learning, and Deep Learning
- Advantages of Deep Learning
- Neural Network Layers
- Weights and Biases
- Activation Functions
- Perceptron
- AND, OR, and XOR problems
- Sigmoid, Tanh, and ReLU
- Vanishing Gradient Problem
- Neural Network Training Cycle

---

# Part II. Programming

## 1. Tensor Manipulations & Reshaping

### Tasks

- Create a random tensor with shape `(4, 6)`.
- Find the rank and shape of the tensor.
- Reshape the tensor to `(2, 3, 4)`.
- Transpose the tensor to `(3, 2, 4)`.
- Apply broadcasting using a smaller tensor with shape `(1, 4)`.
- Add the tensors using TensorFlow broadcasting.

### Key Concepts

This section demonstrates tensor rank, shape, reshaping, transposing, and broadcasting in TensorFlow.

Broadcasting allows TensorFlow to automatically expand a smaller tensor when the tensor dimensions are compatible.

---

## 2. Loss Functions & Hyperparameter Tuning

### Tasks

- Define the true values and model predictions.
- Calculate Mean Squared Error (MSE).
- Calculate Categorical Cross-Entropy (CCE).
- Modify the prediction values.
- Compare the loss values.
- Visualize the loss values using a Matplotlib bar chart.

### Results

The experiment shows that when the prediction becomes closer to the true label, both MSE and Categorical Cross-Entropy decrease.

For example:

- Original prediction: `[0.7, 0.2, 0.1]`
- Modified prediction: `[0.8, 0.1, 0.1]`
- True label: `[1, 0, 0]`

The modified prediction is closer to the true label, resulting in lower loss values.

---

## 3. Train a Model with Different Optimizers

### Tasks

- Load the MNIST dataset.
- Create a neural network model.
- Train one model using Adam.
- Train another model using SGD.
- Compare training and validation accuracy.
- Plot the accuracy trends.

### Model Architecture

Both models use the same neural network architecture:

```text
Input: 28 × 28
      ↓
Flatten
      ↓
Dense: 128 neurons, ReLU
      ↓
Dense: 10 neurons, Softmax
