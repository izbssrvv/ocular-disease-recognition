# Ocular Disease Recognition using CNN

## Overview

This project focuses on automatic ocular disease recognition from retinal fundus images using a Convolutional Neural Network (CNN) built from scratch. The objective is to classify eye diseases based on image data and evaluate the effectiveness of preprocessing techniques and hyperparameter optimization.

## Project Objectives

* Develop a CNN model from scratch for ocular disease classification.
* Apply image preprocessing techniques to improve model performance.
* Evaluate the model using multiple classification metrics.
* Compare the final model against a baseline model without preprocessing or data augmentation.
* Perform hyperparameter tuning to identify the optimal model configuration.

## Dataset

The project uses retinal fundus images from the ODIR (Ocular Disease Intelligent Recognition) dataset. The dataset contains images labeled with different ocular conditions and normal cases.

## Data Preprocessing

The following preprocessing techniques were applied:

1. **Image Resizing**

   * All images were resized to a fixed resolution suitable for CNN training.

2. **Image Normalization**

   * Pixel values were scaled to the range [0, 1] to improve training stability and convergence.

## Model Architecture

A custom Convolutional Neural Network (CNN) was implemented from scratch using deep learning frameworks.

The architecture consists of:

* Convolutional layers for feature extraction
* ReLU activation functions
* Max-pooling layers for spatial downsampling
* Fully connected layers for classification
* Softmax output layer for multi-class prediction

## Hyperparameter Tuning

Hyperparameter optimization was performed to improve model performance. The following parameters were explored:

* Learning rate
* Batch size
* Number of convolutional filters
* Number of hidden units
* Dropout rate
* Number of training epochs

The best-performing configuration was selected based on validation performance.

## Performance Evaluation

Model performance was evaluated using the following metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC

These metrics provide a comprehensive assessment of classification performance across different disease categories.

## Baseline Comparison

A baseline CNN model was trained without preprocessing and data augmentation.

The final model was compared against the baseline to evaluate the impact of:

* Image resizing
* Image normalization
* Hyperparameter tuning



## Technologies Used

* Python
* PyTorch
* NumPy
* Pandas
* OpenCV
* Matplotlib
* Scikit-learn


```

## Conclusion

This project demonstrates the effectiveness of a custom CNN for ocular disease recognition. Through preprocessing and hyperparameter tuning, the final model significantly outperformed the baseline model and achieved reliable classification performance on retinal fundus images.
