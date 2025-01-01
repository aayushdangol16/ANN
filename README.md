# Simple Artificial Neural Network (ANN) from Scratch

This project involves the development of a simple Artificial Neural Network (ANN) with two hidden layers, implemented from scratch. The model includes features such as batch normalization, Leaky ReLU activation, softmax, cross-entropy loss, and dropout. Additionally, gradients are manually computed and compared with those obtained using autograd. The model is trained on the MNIST dataset.

## Features

- **Two Hidden Layers**: A simple architecture with two hidden layers for training the ANN.
- **Batch Normalization**: Implemented to improve training speed and stability.
- **Leaky ReLU Activation**: Applied to the hidden layers to allow small gradients when the input is less than zero.
- **Softmax**: Used for the output layer to convert logits into probabilities.
- **Cross-Entropy Loss**: Loss function used for multi-class classification.
- **Dropout**: Applied during training to reduce overfitting.
- **Manual Gradient Computation**: Gradients are manually computed and compared with autograd gradients to ensure correctness.
- **MNIST Dataset**: The model is trained and evaluated on the MNIST dataset, a well-known collection of handwritten digits.
