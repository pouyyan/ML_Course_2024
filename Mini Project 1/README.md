# Exploring Machine Learning Concepts

This repository demonstrates the use of classification models and hyperparameter tuning techniques for a synthetic dataset, user-drawn data, Feature Extraction for Tome series Bearing dataset and LS, RLS and WLS for Weather dataset.

## Links

||Google Drive <br />(including the <br /> LaTeX report file)|Google Colab|
|---|---|---|
| Links | [![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/186AbdIeFw0kJYwt5gFSpX7yTnF4EynGj?usp=sharing) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1al77_chJL7QaaN7ua8sv6XHlA3DeEKfW/view?usp=sharing) |


This notebook provides a comprehensive guide to classification models and hyperparameter tuning, offering both theoretical understanding and practical application.


## Requirements
To run the code, ensure you have the following installed:

Python 3.x

Jupyter Notebook (for running interactively)

## Setup

Run Jupyter Notebook or any Python environment that supports interactive sessions.

## Overview

### Question 1: Classification Models and Hyperparameter Tuning

1. **Dataset Creation and Visualization:**  Generates a 3D dataset and visualizes it using Matplotlib.

2. **Logistic Regression and SGD Classifier:** Trains and evaluates both models on the generated dataset.

3. **Hyperparameter Tuning:**  Employs Bayesian optimization to find optimal hyperparameters for both models, enhancing their performance.

4. **Decision Boundary Visualization:**  Plots the 3D decision boundaries of the trained models.

5. **Interactive Data Drawing:**  Enables users to draw scatter plot data using the 'drawdata' library.

6. **Model Training and Evaluation on Drawn Data:**  Trains and evaluates Logistic Regression and SGD Classifier on the user-drawn dataset.

7. **Hyperparameter Tuning on Drawn Data:**  Optimizes hyperparameters for both models on the user-drawn data.

8. **Decision Boundary Visualization on Drawn Data:**  Displays the decision boundaries of the trained models on the user-drawn data.

### Question 2

Bearing Fault Detection: Imports and preprocesses vibration data from bearings with different fault conditions.

Feature Extraction: Performs feature extraction by calculating statistical features from time-series data.

Logistic Regression: Writing Logistic Regression from Scratch and Apply it on the data 

### Question 3

Drug Classification:

Loads a dataset on Weather.

Computing Correlation Matrix for selected Features and Plot Heatmap and Histogram.

Writing from Scratch Class for LS and RLS

Apply WLS

## Code Structure:

The code is organized into separate Python scripts, corresponding to the exploration of different concepts:

Question 1: Activation functions and McCulloch-Pitts neurons

Question 2: Bearing fault detection

Question 3: LS, RLS and WLS on Weather dataset

## Code Organization

| Code Section | Description |
|---|---|
| Question 1 part 2 | Creating Dataset |
| Question 1 part 3 | Logistic Regression and SGD Classifierand tunning their hyperparameters |
| Question 1 part 4 | Plotting 3D Decision Boundary |
| Question 1 part 5 | Making data using Scatter Draw, Linear CLassification and Hyperparameter Tunnin, Decision Boundary |
| Question 2 part 1 | Import Bearing Dataset |
| Question 2 part 2 | Extract M*N Windows and Features, Shuffling and Normalization|
| Question 3 part 1 | Import Weather Dataset, PLot Correlation Heatmap, Histogram |
| Question 3 part 2 | LS for Temp and Apparent Temp, RLS for Temp and Apparent Temp, WLS for Temp and Apparent Temp |


## Running Examples
Example usage can be found in Mini_Project_1.ipynb.

## References

Opendatasets

## License

This project is licensed under the MIT License - see the LICENSE file for details.

