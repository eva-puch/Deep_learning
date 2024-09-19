# Deep Learning Reports

This repository contains one report completed as part of the **Deep Learning** course taught in the MSc. program of Data Science at the *French National School of Statistics and Analysis of Information* (*ENSAI*).

## 📋 Overview

# Report 1: CIFAR-10 Dataset Analysis
In this report we work with the CIFAR-10 dataset (Krizhevsky 2009). The objective is to adapt the dataset to the PyTorch format, allowing for effective training and evaluation of models. Key tasks include:
- **Data Preparation**: Downloading the dataset, converting it to NumPy arrays, and grayscale images.
- **Dataset Splitting**: Splitting into training and validation sets, and converting to PyTorch tensors.
- **Custom Dataset**: Implementing a `CustomDataset` class and creating DataLoaders.
- **MLP Model**: Building a 5-layer Multi-Layer Perceptron (MLP) with ReLU activations.
- **Training & Evaluation**: Functions for model training with mini-batches and evaluating performance.
- **Batch Normalization**: Creating a batch-normalized version of the MLP.
- **CNNs**: Implementing and training a LeNet5 model, comparing it to the MLP.
- **Transfer Learning**: Fine-tuning a pre-trained ResNet18 on a subset of CIFAR-10.


## 📚 Course Information
- **Course**: Deep Learning
- **Instructor**: Mr. Yamane
- **Institution**: National School of Statistics and Analysis of Information (ENSAI)
- **Program**: MSc. in Data Science and Statistics
- **Year**: 2023
