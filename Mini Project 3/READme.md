##Iris Dataset Analysis and SVM Classification
This repository contains Python scripts for analyzing the Iris dataset using machine learning techniques, specifically Support Vector Machines (SVM) with Linear Discriminant Analysis (LDA) and polynomial kernels.

###Overview
The scripts provided perform the following tasks:

Data Analysis: Exploratory data analysis (EDA) of the Iris dataset, including visualizations and statistical summaries.
Data Preprocessing: Standardization of data and dimensionality reduction using LDA.
SVM Classification: Training SVM models with different kernels (linear and polynomial) for species classification.
Custom SVM Implementation: Implementation of a custom SVM class (MySVM) for polynomial kernel SVMs from scratch.
Visualization: Plotting decision boundaries and generating a GIF animation of polynomial SVM decision boundaries using the custom implementation.
Fraud Detection: Analysis of credit card fraud data using oversampling (SMOTE), denoising autoencoder, and classification.
Libraries Used
pandas, numpy: Data handling and manipulation.
matplotlib, seaborn: Data visualization.
scikit-learn: Machine learning models (SVM, LDA, train-test split, metrics).
imageio: Creating GIF animations.
cvxopt: Optimization library for SVM.
tensorflow, keras: Deep learning framework for autoencoder implementation.
Files
iris_analysis.py: Script for data analysis and visualization of the Iris dataset.
svm_classification.py: Script for SVM classification with LDA and linear kernel.
polynomial_svm.py: Script for polynomial SVM classification and decision boundary visualization.
custom_svm.py: Implementation of custom SVM class (MySVM) for polynomial kernel SVMs.
credit_card_fraud_detection.py: Script for fraud detection using oversampling (SMOTE), denoising autoencoder, and classification.
Usage
Setup: Ensure Python 3.x and required libraries are installed (pip install -r requirements.txt).

Run Scripts:

Execute iris_analysis.py to perform exploratory data analysis and generate visualizations for the Iris dataset.
Run svm_classification.py for SVM classification with linear kernel and LDA on the Iris dataset.
Use polynomial_svm.py to explore polynomial SVMs with varying degrees and generate decision boundary animations.
Explore custom_svm.py to understand the implementation of polynomial SVM from scratch and visualize decision boundaries.
Execute credit_card_fraud_detection.py for fraud detection using oversampling, denoising autoencoder, and classification on credit card fraud data.
Output:

Various plots and visualizations will be saved in the respective directories.
Decision boundary animations (SVM_Scratch_decision_boundaries.gif) will be created showcasing polynomial SVMs implemented from scratch.
Results and metrics for fraud detection will be printed to evaluate model performance.
Notes
Adjust parameters and experiment with different settings to explore machine learning and deep learning concepts further.
Contributions and feedback are welcome. Feel free to fork and modify the repository.
