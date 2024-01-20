# Face Mask Detection

## Overview

This project implements a face mask detection system using a Convolutional Neural Network (CNN) model. The model is trained to classify whether a person is wearing a face mask or not.

## Prerequisites

- Python 3.x
- TensorFlow
- OpenCV
- sklearn
- keras
- Image
- numpy
- matplotlib

## Data Preprocessing

- The images are loaded, resized, and normalized to prepare them for training.

## Model Architecture

The CNN model consists of several convolutional layers followed by max-pooling layers. The final layer uses softmax activation to predict the color category.

## Data Augmentation

Data augmentation techniques are employed to enhance the model's generalization by applying random transformations to the training images.

## Training

The model is trained using the training dataset with the Adam optimizer and categorical crossentropy loss. Callbacks such as ModelCheckpoint, ReduceLROnPlateau, and EarlyStopping are used to monitor and improve training performance.


