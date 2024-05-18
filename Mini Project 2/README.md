# Mini-Project 2: Exploring Machine Learning Concepts

This repository contains Python code that explores various concepts in Machine Learning, including:

Activation Functions: Implements sigmoid and ReLU activation functions, calculates their derivatives, and plots them.
McCulloch-Pitts Neurons: Defines a McCulloch-Pitts neuron class and uses it to create a simple neural network for linear classification.
Bearing Fault Detection:
Imports and preprocesses vibration data from bearings with different fault conditions.
Performs feature extraction by calculating statistical features from time-series data.
Implements 3-layer neural networks with different optimizers and loss functions for bearing fault classification.
Evaluates model performance using classification reports and confusion matrices.
Uses 5-fold cross-validation to assess model generalization.
Drug Classification:
Loads a dataset on drug properties and diagnoses.
Performs label encoding for categorical features.
Implements and trains decision tree classifiers to classify drugs based on their properties.
Analyzes the impact of hyperparameter changes (max_depth, max_leaf_nodes, ccp_alpha) on classification performance.
Explores potential improvements using techniques like undersampling (work in progress).
Heart Disease Prediction: (Code Snippet Included)
Downloads and prepares the heart disease dataset.
Splits the data into training and testing sets.
Performs data standardization using standard scaling.
Trains a Naive Bayes classifier for heart disease prediction.
Evaluates model performance using accuracy score, classification report, and confusion matrix.
Provides sample predictions on a small subset of test data.

## Code Structure:

The code is organized into separate Python scripts, corresponding to the exploration of different concepts:

Question 1: Activation functions and McCulloch-Pitts neurons

Question 2.py: Bearing fault detection

Question 3.py: Drug classification (including undersampling exploration)

Question 4.py: Heart disease prediction

## Requirements:

This code assumes you have the following libraries installed:
pandas
numpy
seaborn
tensorflow
keras
scikit-learn
opendatasets (for Heart Disease dataset download in Code4.py)
gdown (for downloading the Heart Disease dataset in Code4.py)

## Instructions:

Clone this repository to your local machine.
Install the required libraries (pip install <library_name> for each).
Run the Python scripts individually (e.g., python Code1_1.py) to explore different concepts.
For Code4.py (Heart Disease prediction): Ensure you have opendatasets and gdown installed.
