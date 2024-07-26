# CIFAR-10 Image Classification with CNN

This project focuses on building and training a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset. The model is trained using data augmentation techniques to improve its performance and generalization.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Data Augmentation](#data-augmentation)
- [Training](#training)
- [Evaluation](#evaluation)

## Overview

This project aims to build a robust CNN model for image classification using the CIFAR-10 dataset. The model incorporates data augmentation, batch normalization, dropout layers, and a learning rate scheduler to enhance its performance.

## Dataset

The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. There are 50,000 training images and 10,000 test images.

## Model Architecture

The model consists of convolutional, batch normalization, max-pooling, dropout, and dense layers. The architecture is designed to capture complex patterns and features from the images.

## Data Augmentation

Data augmentation techniques are used to artificially create variations of the training data, which helps improve the model's ability to generalize. The following augmentations are applied:
- Rotation (up to 15 degrees)
- Width and height shifts (up to 10% of the image size)
- Horizontal flip

## Training

The model is trained using the Adam optimizer with a learning rate scheduler to adjust the learning rate during training. The training process includes:
- Data augmentation
- Batch normalization
- Dropout for regularization

## Evaluation

The model's performance is evaluated using the test dataset. The accuracy and loss are recorded and visualized to assess the model's performance.


