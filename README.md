# Digit Recognition with Convolutional Neural Networks

This repository contains the code for training and evaluating a convolutional neural network (CNN) for digit recognition using the MNIST dataset.

## Model Architecture

The CNN architecture used for digit recognition consists of the following layers:

1. **Convolutional Layers**: 
   - Two sets of convolutional layers with 32 filters each, kernel size of 5x5, and ReLU activation.
   - Max pooling layers with a pool size of 2x2.
   - Dropout layers with a dropout rate of 25% to prevent overfitting.

2. **Dense Layers**:
   - Two fully connected dense layers with 256 units and ReLU activation.
   - Dropout layer with a dropout rate of 50%.

3. **Output Layer**:
   - Dense output layer with 10 units (one for each digit) and softmax activation.

## Training

The model was trained using the RMSprop optimizer with sparse categorical cross-entropy loss for 10 epochs.
