# Basic Perceptron Implementation with NumPy

Welcome to my Basic Perceptron project! This repository features a simple implementation of a single-layer perceptron built using NumPy.

## Project Overview

This project generates random data to predict an outcome \(y\) based on two independent variables \(x_1\) and \(x_2\). The perceptron uses the following key components:

- **Data Generation**: Random data is created using Python's `random` library.
- **Independent Variables**: \(x_1\) and \(x_2\) serve as the features for prediction.
- **Forward Pass**: A function named `forward_pass` calculates the output based on current weights and inputs.
- **Weight Update**: The `weights_update` function adjusts the weights and biases based on the error during training.
- **Error Minimization**: The model iteratively reduces the error to approximately 0.594.

## Features

- Implemented using Python and NumPy.
- Functions for forward propagation and weight updates.
- Randomly generated dataset for binary classification.
- Manual upgrade of iterations to minimize error.

## Installation

To run this project, ensure you have Python and NumPy installed. You can install NumPy using pip:

```bash
pip install numpy matplotlib

