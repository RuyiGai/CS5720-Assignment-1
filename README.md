# CS5720 Neural Network and Deep Learning - Home Assignment 1

## Student Information

- **Name:** Ruyi Gai
- **Course:** CS5720 Neural Network and Deep Learning
- **Semester:** Fall 2026
- **University:** University of Central Missouri

## Assignment Overview

This assignment focuses on fundamental neural network concepts and TensorFlow programming.

The assignment includes:

- Tensor Manipulation & Reshaping
- Broadcasting
- Loss Functions (MSE and Categorical Cross-Entropy)
- Adam vs. SGD Optimizers
- MNIST Neural Network Training
- TensorBoard Visualization
- Overfitting Analysis

## TensorBoard Experiment

TensorBoard was used to monitor the training and validation accuracy and loss of the neural network.

The model was trained for **5 epochs** and **10 epochs** to compare the effect of increasing the number of epochs.

The TensorBoard logs are stored in:

```text
logs/fit/
```

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

The Jupyter Notebook contains the source code and experiments. The code is appropriately commented to explain the main steps.

## Conclusion

This assignment provided practical experience with TensorFlow, neural network training, loss functions, different optimizers, and TensorBoard. The experiments demonstrated how increasing the number of epochs can improve training performance, while excessive training may eventually lead to overfitting.








