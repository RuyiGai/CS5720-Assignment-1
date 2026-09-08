# CS5720 Neural Network and Deep Learning - Home Assignment 1

## Student Information

- **Name:** Ruyi Gai
- **Course:** CS5720 Neural Network and Deep Learning
- **Semester:** Fall 2026
- **University:** University of Central Missouri

## Assignment Overview

This assignment focuses on fundamental neural network concepts and TensorFlow programming.

### Topics Covered

- Tensor Manipulation & Reshaping
- Broadcasting
- Loss Functions (MSE and Categorical Cross-Entropy)
- Adam vs. SGD Optimizers
- MNIST Neural Network Training
- TensorBoard Visualization
- Overfitting Analysis

## TensorBoard

TensorBoard was used to monitor training and validation accuracy and loss.

The model was trained for **5 epochs** and **10 epochs** to compare the effect of increasing the number of epochs.

The TensorBoard logs are stored in:

### text
logs/fit/
The 10-epoch experiment achieved approximately:

Training Accuracy: 99.10%
Validation Accuracy: 97.78%
Training Loss: 0.0331
Validation Loss: 0.0742

The validation loss reached its lowest value around epoch 9 and increased slightly at epoch 10, which may indicate the beginning of overfitting.

## Files
Assignment 1.ipynb
README.md
logs/
└── fit/

## Conclusion

This assignment provided practical experience with TensorFlow, neural network training, different optimizers, loss functions, and TensorBoard. The experiments also demonstrated how increasing the number of epochs can improve training performance but may eventually lead to overfitting.
