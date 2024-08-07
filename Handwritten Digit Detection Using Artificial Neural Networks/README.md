# Handwritten Digit Detection Using Artificial Neural Networks
## Overview
This project focuses on detecting handwritten digits using an Artificial Neural Network (ANN) implemented with TensorFlow and Keras. The model is trained and evaluated using the MNIST dataset, which is a widely-used dataset consisting of 70,000 grayscale images of handwritten digits (0-9).
## Dataset
- Source: Keras MNIST dataset
- Training Set: 60,000 images
- Test Set: 10,000 images
## Project Structure
### 1. Data Loading and Preprocessing

Importing necessary libraries (TensorFlow, Keras, NumPy, Matplotlib, Seaborn).
Loading the MNIST dataset.
Visualizing sample images from the dataset.
Normalizing the image data by flattening and scaling pixel values.

### 2. Model Building

- Constructing an ANN model with Dense Layer(keras.layers.Dense).
- Using activation functions sigmoid.
