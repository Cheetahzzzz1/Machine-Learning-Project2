# Machine Learning Project 2

# Overview

This project aims on building and evaluating two types of neural networks to classify handwritten digits from the MNIST dataset:

 1. Feedforward Neural Network (FFNN)

 2. Convolutional Neural Network (CNN)

The goal is to achieve a higher testing accuracy (>95%) using both models and analyse thier performance over multiple training runs.

# Files Included 

1. train-images.idx3-ubyte: Training images (28x28 grayscale)

2. train-labels.idx1-ubyte: Labels for the training images

3. t10k-images.idx3-ubyte: Test images (28x28 grayscale)

4. t10k-labels.idx1-ubyte: Labels for the test images

# Project Structure

<ins> Preprocessing </ins>

1. Normalizes pixel values to [0,1].

2. Converts labels to one-hot encoding.

<ins> Feedforward Neural Network </ins>

1. Uses dense layers with ReLu activation.

2. Regularized with dropout layers.

<ins> Convolutional Neural Network </ins>

1. Includes Convolutional layers with 3x3 filters.

2. Max pooling and dropout for dimensionality reduction and regularization.

# Code Implementation

The entire project has been implemented on google colab environment. The relevant libraries that have been used are:

1. Tensorflow

2. NumPy

3. MNIST dataset in idx format
