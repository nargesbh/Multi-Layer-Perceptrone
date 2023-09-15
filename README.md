# Multi-Layer Perceptron (MLP) Implementation from Scratch
![mlp_gif](ANN-Graph.gif)


This repository contains a Python implementation of a Multi-Layer Perceptron (MLP) from scratch. The MLP is designed to handle classification tasks. The code includes the construction of the MLP class, forward and backward propagation, training functionality, and an example of its usage on a specific dataset.

## Table of Contents

- [Introduction](#introduction)
- [MLP Architecture](#mlp-architecture)
- [Usage](#usage)
- [Results](#results)
- [Visualization](#visualization)

## Introduction

This Python code provides an implementation of a Multi-Layer Perceptron (MLP), a type of artificial neural network (ANN). ANNs are widely used in machine learning and deep learning for various tasks, including classification. This MLP is built from scratch, allowing for a better understanding of its inner workings.

## MLP Architecture

The MLP architecture consists of an input layer, one or more hidden layers, and an output layer. The number of neurons in each layer is configurable. The key components of this MLP implementation are as follows:

- **MLP Class**: The core class representing the MLP model.
- **Sigmoid Function**: A method for applying the sigmoid activation function.
- **Sigmoid Derivative**: A method for computing the derivative of the sigmoid function.
- **Gradient Descent**: A method for updating the weights using gradient descent.
- **Forward Propagation**: A method for making predictions by passing input through the network layers.
- **Back Propagation**: A method for updating weights based on the prediction error.
- **Training Function**: A method for training the MLP on input data and target labels.
- **File Reading**: Functions for reading training and testing data from files.

## Usage

To use this MLP implementation, follow these steps:

1. Prepare your training and testing data files. Each file should contain rows of input features (space-separated) followed by the corresponding target label (0 or 1). See the provided "train" and "test" files for examples.

2. Initialize the MLP with the desired architecture by creating an instance of the `MLP` class, specifying the number of input neurons, hidden layer sizes, and the number of output neurons.

3. Train the MLP using the `train` method, passing your training data, the target labels, the number of epochs, and the learning rate (alpha) as parameters.

4. Use the trained MLP to make predictions on test data using the `forward_propagate` method.

5. Analyze the results and visualize them as needed.

## Results

After training the MLP, you can expect to see the training completion message and the accuracy achieved on your specific dataset.

## Visualization

The code includes a visualization of the points predicted by the MLP. Blue points represent those predicted as 1, and red points represent those predicted as 0. This visualization can help you understand how well the MLP is performing on your dataset.

Feel free to modify and experiment with the architecture and hyperparameters to achieve the best results for your specific classification task. Happy coding!
