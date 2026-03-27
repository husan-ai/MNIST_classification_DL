# Deep Learning Project: MNIST Digit Classification (DL_project)

This repository contains a deep learning project built using PyTorch to classify handwritten digits from the MNIST dataset.

---

## About

This project demonstrates a complete deep learning pipeline including data loading, preprocessing, model building, training, and evaluation.

The model is trained to recognize digits from **0 to 9** using grayscale images of size **28x28 pixels**.

---

## Model Architecture

The neural network is implemented using `nn.Sequential`:

* Input layer: 784 neurons (28x28 pixels)
* Hidden layer: 128 neurons with ReLU activation
* Output layer: 10 neurons (digit classes 0–9)

---

## Technologies Used

* Python
* PyTorch
* Torchvision
* Matplotlib

---

## Training Details

* Loss Function: CrossEntropyLoss
* Optimizer: SGD (learning rate = 0.01)
* Epochs: 5
* Batch size: 64

---

## Workflow

* Data loading using Torchvision
* Data transformation (Tensor conversion)
* Model creation (Neural Network)
* Training loop (forward + backward pass)
* Loss tracking and visualization

---

## Results

The training loss decreases over epochs, showing that the model learns effectively from the data.

A loss graph is plotted after training.

---

## Purpose

The goal of this project is to understand the fundamentals of deep learning and implement a neural network using PyTorch.

---

## Future Improvements

* Add Convolutional Neural Network (CNN)
* Improve accuracy using advanced optimizers (Adam)
* Add validation and accuracy metrics
* Experiment with different architectures

---

## Author 
Muhammadiyev Husan 
GitHub: https://github.com/husan-ai 
