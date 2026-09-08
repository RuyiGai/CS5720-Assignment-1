# CS5720 Neural Network and Deep Learning - Home Assignment 1

## Student Information

- **Name:** Ruyi Gai
- **Student ID:** 700778329
- **Course:** CS5720 Neural Network and Deep Learning
- **Semester:** Fall 2026
- **University:** University of Central Missouri

## Assignment Overview

This assignment covers fundamental neural network concepts and practical TensorFlow programming. It includes both short-answer questions and programming tasks.

## Part I: Short Answer Questions

The short-answer section covers fundamental concepts of neural networks, including:

- Traditional Programming vs. Machine Learning
- Artificial Intelligence, Machine Learning, and Deep Learning
- Advantages of Deep Learning
- Neural Network Layers
- Weights and Biases
- Activation Functions
- Perceptron
- AND, OR, and XOR Problems
- Sigmoid, Tanh, and ReLU
- Vanishing Gradient Problem
- Neural Network Training Cycle

These questions provide a foundation for understanding how neural networks work and how they are trained.

## Part II: Programming Tasks

### 1. Tensor Manipulation & Reshaping

A random tensor was created to practice tensor rank, shape, reshaping, transposing, and broadcasting operations using TensorFlow.

### 2. Loss Functions

Mean Squared Error (MSE) and Categorical Cross-Entropy (CCE) were calculated using different predictions. The loss values were compared to demonstrate how prediction quality affects model loss.

### 3. Adam vs. SGD Optimizers

Two neural network models were trained on the MNIST dataset using the Adam and SGD optimizers. Training and validation accuracy were compared to observe the effect of different optimizers on the training process.

### 4. TensorBoard Experiment

A neural network was trained on the MNIST dataset and TensorBoard was used to monitor training and validation accuracy and loss.

The model was trained for **5 epochs** and **10 epochs** to compare the effect of increasing the number of training epochs.

For the 10-epoch experiment, the model achieved approximately:

- **Training Accuracy:** 99.10%
- **Validation Accuracy:** 97.78%
- **Training Loss:** 0.0331
- **Validation Loss:** 0.0742

The validation loss reached its lowest value around epoch 9 and increased slightly at epoch 10. This may indicate the beginning of overfitting.

## Files

```text
Assignment 1.ipynb
README.md
logs/
└── fit/
```

The Jupyter Notebook contains the answers to Part II: Programming Tasks. The code is appropriately commented to explain the main steps.

The `logs/fit/` folder contains the TensorBoard log files generated during the experiments.

## Conclusion

This assignment provided both theoretical and practical experience with neural networks and TensorFlow. The short-answer questions covered fundamental neural network concepts, while the programming tasks provided hands-on experience with tensor operations, loss functions, optimizers, MNIST classification, and TensorBoard.

The experiments also demonstrated that increasing the number of epochs can improve training performance, while excessive training may eventually lead to overfitting.




