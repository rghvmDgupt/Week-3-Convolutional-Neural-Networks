# Week 3 - Convolutional Neural Networks

## Author

**Raghavam Gupta**
B.Tech, IIT (BHU) Varanasi

---

## Overview

This repository contains the implementation of three deep learning tasks completed as part of the Week 3 Convolutional Neural Networks assignment. All models were implemented from scratch using PyTorch without using pretrained architectures.

The primary objective of this assignment was to understand CNN architectures, data preprocessing, model training, validation, and evaluation.

---

## Repository Structure

```text
Week3/
├── Task0GTSRB_CNN.ipynb
├── Task1_PilotNet.ipynb
├── Task2_ResNet18.ipynb
├── pilotnet_task1.pth
├── resnet18_task2.pth
├── Task0_Report.docx
├── Task1_Report.docx
├── Task2_Report.docx
└── README.md
```

---

## Task 0: Custom CNN for Traffic Sign Recognition

### Dataset

German Traffic Sign Recognition Benchmark (GTSRB)

### Objective

Design and train a custom Convolutional Neural Network from scratch for traffic sign classification.

### Architecture

* Convolution Layers
* Batch Normalization
* ReLU Activation
* Max Pooling
* Fully Connected Layers
* Dropout Regularization

### Results

* Validation Accuracy: **99.35%**
* Training and Validation loss curves generated.
* Confusion matrix generated for performance analysis.

---

## Task 1: Behavioral Cloning using NVIDIA PilotNet

### Dataset

CARLA Steering Dataset

### Objective

Implement NVIDIA's PilotNet architecture to predict steering angles directly from camera images.

### Architecture

* 5 Convolutional Layers
* Fully Connected Layers
* Regression Output Layer

### Results

* Successfully trained on CARLA dataset.
* Mean Squared Error (MSE) loss used for optimization.
* Training and validation losses decreased consistently.

---

## Task 2: ResNet-18 from Scratch

### Dataset

German Traffic Sign Recognition Benchmark (GTSRB)

### Objective

Implement the ResNet-18 architecture from scratch using residual connections without using pretrained models.

### Architecture

* Residual Blocks
* Skip Connections
* Batch Normalization
* ReLU Activation
* Global Average Pooling
* Fully Connected Classification Layer

### Results

* Validation Accuracy: **99.55%**
* Training and validation loss curves generated.
* Sample predictions visualized.
* Confusion matrix generated.

---

## Technologies Used

* Python
* PyTorch
* Torchvision
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---


## Conclusion

This assignment provided hands-on experience with:

* Building CNNs from scratch
* Training deep neural networks
* Implementing residual learning
* Regression and classification tasks
* Model evaluation and visualization

The completed tasks demonstrate a strong understanding of modern convolutional neural network architectures and deep learning workflows.
