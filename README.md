# MNIST Digit Recognition with Deep Learning

## Overview

This project, developed as part of academic cursus of the MSc in Bioinformatics, explores the application of various deep learning architectures to recognize digits from a modified version of the MNIST dataset. The original MNIST images have been altered by adding noise and applying transformations. The project implements and compares different neural network models to assess their performance on this modified dataset.

## Objective

The main objective of this project is to develop and compare different deep learning models for digit recognition using a modified MNIST dataset. By implementing various architectures and evaluating their performance, we aim to identify the most robust approach for recognizing digits in the presence of noise and transformations.

## Features

The project implements and compares the following deep learning architectures:

1. Simple Deep Neural Network (DNN)
2. Basic Convolutional Neural Network (CNN)
3. Optimised Convolutional Neural Network (Optim. CNN)

## Results

The following table summarizes the accuracy results for each model:

| Model     | Accuracy |
|-----------|----------|
| DNN       | 82.36%   |
| CNN       | 91.33%   |
| CNN_Optim | 95.75%   |

As we can see, the optimized CNN model (CNN_Optim) achieved the highest accuracy on the modified MNIST dataset, followed by the basic CNN, with the DNN showing the lowest accuracy among the three.