#  Build Neural Networks from Scratch

This repository contains **two neural network projects implemented from scratch using NumPy**, demonstrating **forward/backward propagation, training loops, and practical applications** in healthcare and image recognition. Both projects are available as **Jupyter notebooks**.

---

## Project 1: Neural Network on Breast Cancer Wisconsin Dataset

###  Objective
Implement a **fully connected feedforward neural network** to classify **tumors as malignant or benign** using the **Breast Cancer Wisconsin dataset** from scikit-learn.

###  Features
- Forward and backward propagation implemented manually  
- ReLU activation for hidden layer  
- Sigmoid activation for output layer  
- Binary cross-entropy loss  
- Gradient descent optimization  
- Accuracy evaluation on test data  

### 📊 Results
- Test Accuracy: ~95%  
- Loss decreases smoothly during training  

### 🧬 Biomedical Relevance
- Demonstrates application of a neural network to **tabular biomedical data**  
- Useful for diagnostic predictions, e.g., cancer detection

---

## Project 2: Neural Network on MNIST Dataset (28×28 Images)

###  Objective
Build a feedforward neural network to classify **handwritten digits (0–9)** from the **MNIST dataset** using **NumPy only**.

###  Features
- Input layer: 784 neurons (flattened 28×28 images)  
- Hidden layer: 128 neurons with ReLU activation  
- Output layer: 10 neurons with softmax activation  
- Categorical cross-entropy loss  
- Mini-batch gradient descent  
- Visualization of loss and accuracy curves  
- Sample predictions for test images  

### 📊 Results
- Test Accuracy: ~92–95%  
- Loss curve decreases over epochs  
- Correct digit predictions visualized  

### 🧬 Relevance
- Demonstrates handling of **image data**  
- Skills transferable to **medical imaging**, e.g., tumor detection, histopathology, radiology


