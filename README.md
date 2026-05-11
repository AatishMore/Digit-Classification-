# Digit-Classification
# MNIST Digit Classification using PyTorch

A complete deep learning project that builds, trains, and evaluates a Neural Network to recognize handwritten digits (0–9) using the MNIST dataset. This project demonstrates a full machine learning pipeline using PyTorch, including training loops, evaluation, and real-image prediction.

---

##  Project Overview

This project implements a fully connected Neural Network (Feedforward Neural Network) using PyTorch to classify handwritten digits from the MNIST dataset. It also includes testing on custom images.

---

##  Dataset

- Dataset: MNIST (Modified National Institute of Standards and Technology)
- 60,000 training images
- 10,000 test images
- Image size: 28x28 grayscale
- Classes: 0 to 9

---

##  Model Architecture

The model is a simple Fully Connected Neural Network:

- Input Layer: 784 neurons (28x28 image flattened)
- Hidden Layer 1: 512 neurons + ReLU + Dropout (0.3)
- Hidden Layer 2: 256 neurons + ReLU + Dropout (0.3)
- Output Layer: 10 neurons (digit classes 0–9)

---

##  Technologies Used

- Python 
- PyTorch 
- Torchvision
- NumPy
- Matplotlib
- PIL (Image Processing)

---

##  Training Pipeline

1. Load MNIST dataset
2. Normalize and transform images
3. Build neural network model
4. Define loss function (CrossEntropyLoss)
5. Use Adam optimizer
6. Train using backpropagation
7. Evaluate on test dataset

---

##  Results

- Model trained for 5 epochs
- Evaluated using test accuracy
- Achieved good performance on MNIST dataset
- Includes dropout to reduce overfitting

---

##  Custom Image Prediction

The model can predict handwritten digits from custom images:

Steps:
- Load image
- Resize to 28x28
- Convert to grayscale
- Invert colors (MNIST style)
- Predict digit using trained model

---

##  Save & Load Model
