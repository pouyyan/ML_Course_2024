# Exploring Machine Learning Concepts

This repository contains Python code that explores various concepts in Machine Learning, including Activation Functions, McCulloch-Pitts Neurons, Bearing Fault Detection, Feature Extraction and MLP Classification, Evaluation, Drug Classification using Decision Tree.

## Links

||Google Drive <br />(including the <br /> LaTeX report file)|Google Colab|
|---|---|---|
| Links | [![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1mfLYpc_4aFhffiWJLGMFvEpsZVjRL4nY?usp=sharing) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1hkSkW3U7vCPZx4v2mO12hnxHcw5jqW2e?usp=sharing) |


## Requirements
To run the code, ensure you have the following installed:

- Python 3.x
- Jupyter Notebook (for running interactively)
- Required Python libraries: `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `imblearn`, `tensorflow`, `opendatasets`, `gdown`, `random`
- Jupyter Notebook (for running interactively)

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
| Question 1 part 1 & 2| Plotting Sigmoid, ReLU , ELU and their derivatives |
| Question 1 part 3 | McCulloch-Pitts Neuron Class |
| Question 2 part 1 | Import Bearing dataset, plotting datatset, Extracting M*N windows, Extract Features, Shuffle and Normalization of Data |
| Question 2 part 2 | Design MLP, Plot Loss Curve and Accuracy, Confusion Matrix and Classification Report |
| Question 2 part 3 | Assess the MLP with different Optimizer and Loss Function |
| Question 2 part 4 | Apply K-Fold Cross Validation and K-Fold and Design MLP |
| Question 3 part 1 | Import Drug Dataset, PLot Data, Split Data, Under-Sampling, Decision Tree, Changing Hyperparameters |
| Question 3 part 2 | Random Forest for Original and Under-sampled data, Classification Report, Confusion Matrix |
| Question 4 | Import Heart Disease Dataset, Shuffle and Split, Naive Bayes, Confusion Matrix and Classification Report|


## Running Examples
Example usage can be found in Mini_Project_2.ipynb.

## References
- [Scikit-learn](https://scikit-learn.org/)
- [TensorFlow](https://www.tensorflow.org/)
- [CWRU Bearing Fault Dataset](https://engineering.case.edu/bearingdatacenter/download-data-file)
- [Kaggle Heart Disease Dataset]((https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset))
- [Kaggle Drugs A, B, C, X, Y for Decision Trees](https://www.kaggle.com/datasets/pablomgomez21/drugs-a-b-c-x-y-for-decision-trees)
- 
  
## License

This project is licensed under the MIT License - see the LICENSE file for details.
