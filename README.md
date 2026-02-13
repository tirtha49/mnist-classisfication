# MNIST Handwritten Digit Classification
## 📌 Overview
This mini project demonstrates handwritten digit classification on the MNIST dataset using a simple Deep Learning neural network built with TensorFlow/Keras in a Jupyter Notebook.

The model takes 28×28 grayscale images of digits (0–9), flattens them into a 1D vector, and passes them through fully connected dense layers to perform multi-class classification.

## 🛠️ Model Architecture
Flatten → Dense(128, ReLU) → Dense(10, Softmax)

The neural network consists of:

Flatten Layer : Converts 28×28 pixel images into a 1D vector

Hidden Layer  : Dense layer with 128 neurons using ReLU activation

Output Layer  : Dense layer with 10 neurons using Softmax activation for multi-class classification

## ⚙️ Model Compilation
Loss Function: sparse_categorical_crossentropy

Optimizer: Adam

## 🦾 Technologies Used
Python

TensorFlow / Keras

NumPy

Matplotlib

Jupyter Notebook

## 📝 Features
Data normalization

Model training & evaluation

Accuracy visualization

Digit prediction system

Clean and simple ANN architecture

## 🎯 Results

Achieves ~ 97–98% accuracy on the MNIST classification dataset using a basic ANN model.
