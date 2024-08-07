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
 
### 3. Model Training

- Compiling the model with loss function (categorical crossentropy) and optimizer (Adam).
- Training the model on the training dataset.
- Monitoring the training process using accuracy metrics.

### 4. Model Evaluation

- Evaluating the trained model on the test dataset.
- Calculating and displaying the model's accuracy and loss.
  
### 5. Results Visualization

Plotting confusion matrix to analyze the model performance.
Visualizing sample predictions to compare actual vs predicted labels.

![image](https://github.com/user-attachments/assets/29f8907e-929b-4814-b7b2-8403c8a07553)


## Key Metrics

- Model Accuracy: The logistic regression model achieved an accuracy of 0.82.

## Requirements

- Python 3
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
  
## Instructions

1. Clone the repository and navigate to the project directory.
2. Install the required libraries using pip.
3. Run the colab notebook to see the complete workflow and results.
 
## Conclusion

This project demonstrates the application of ANN for handwritten digit recognition, achieving a substantial accuracy of 0.925. This provides a solid foundation for further enhancements and experimentation with more complex neural network architectures.
