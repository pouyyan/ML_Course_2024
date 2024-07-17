# Exploring Machine Learning Concepts

This repository contains Python code that explores various concepts in Machine Learning, including Activation Functions, McCulloch-Pitts Neurons, Bearing Fault Detection, Feature Extraction and MLP Classification, Evaluation, Drug Classification using Decision Tree.

## Links

||Google Drive <br />(including the <br /> LaTeX report file)|Google Colab|
|---|---|---|
| Links | [![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1cYwwpAv1NShLDwPZEoYb7G_1IoEuYET2/view?usp=sharing) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1hkSkW3U7vCPZx4v2mO12hnxHcw5jqW2e?usp=sharing) |

## Requirements
To run the code, ensure you have the following installed:

Python 3.x

Jupyter Notebook (for running interactively)

## Setup

Run Jupyter Notebook or any Python environment that supports interactive sessions.

## Overview

### Question 1

Activation Functions: Implements sigmoid and ReLU activation functions, calculates their derivatives, and plots them.

McCulloch-Pitts Neurons: Defines a McCulloch-Pitts neuron class and uses it to create a simple neural network for linear classification.

### Question 2

Bearing Fault Detection: Imports and preprocesses vibration data from bearings with different fault conditions.

Feature Extraction: Performs feature extraction by calculating statistical features from time-series data.

MLP Classification: Implements 3-layer neural networks with different optimizers and loss functions for bearing fault classification.

Evaluation: Evaluates model performance using classification reports and confusion matrices.
Uses 5-fold cross-validation to assess model generalization.

### Question 3

Drug Classification:

Loads a dataset on drug properties and diagnoses.

Performs label encoding for categorical features.

Implements and trains decision tree classifiers to classify drugs based on their properties.

Analyzes the impact of hyperparameter changes (max_depth, max_leaf_nodes, ccp_alpha) on classification performance.

Explores potential improvements using techniques like undersampling (work in progress).

### Question 4

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

Question 2: Bearing fault detection

Question 3: Drug classification (including undersampling exploration)

Question 4: Heart disease prediction

## Code Organization

| Code Section | Description |
|---|---|
| dqn_agent | Defines the DQNAgent class for DQN training. |
| ddqn_agent | Defines the DDQNAgent class for DDQN training. |
| utils | Contains utility functions such as experience replay (ExperienceReplay). |
| main | Jupyter Notebook demonstrating agent training and visualization. |

## Running Examples
Example usage can be found in main.ipynb, where DQN and DDQN agents are trained on the LunarLander-v2 environment.

## References

Opendatasets

## License

This project is licensed under the MIT License - see the LICENSE file for details.
