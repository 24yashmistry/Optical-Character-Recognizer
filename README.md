# Simple OCR Model

This repository contains a simple Optical Character Recognition (OCR) model implemented using TensorFlow/Keras. The model is trained to recognize handwritten digits from the MNIST dataset.

## Overview

The OCR model is trained using a simple feedforward neural network architecture with two fully connected layers. The input images are preprocessed, normalized, and flattened before being fed into the neural network. The model is trained using the Adam optimizer and the sparse categorical crossentropy loss function.


## Model Performance
The trained OCR model achieves a test accuracy of approximately 97.8% on the MNIST test set. However, it may not perform equally well on all digits. Further improvements can be made to enhance the model's performance, especially for challenging digits.