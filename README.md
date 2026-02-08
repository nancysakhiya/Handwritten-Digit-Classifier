# Handwritten Digit Classifier (MNIST)

This project implements a **basic handwritten digit recognition system** using a simple Neural Network trained on the **MNIST dataset**.  
It classifies digits from **0 to 9** based on grayscale image inputs.

## Project Overview

- Dataset: MNIST Handwritten Digits
- Model: Single-layer Neural Network
- Framework: TensorFlow / Keras
- Task: Multiclass classification (0–9)

This project is intended as a **beginner-friendly introduction to neural networks and deep learning**.

## Model Architecture

- Input Layer: 784 neurons (28 × 28 image flattened)
- Output Layer: 10 neurons
- Activation Function: Sigmoid
- Loss Function: Sparse Categorical Crossentropy
- Optimizer: Adam

## Dataset

The MNIST dataset consists of:
- 60,000 training images
- 10,000 test images
- Image size: 28 × 28 (grayscale)

Loaded directly using `keras.datasets.mnist`.

## How to Run the Project

### Clone the repository
```bash
git clone https://github.com/your-username/handwritten-digit-classifier.git
cd handwritten-digit-classifier
