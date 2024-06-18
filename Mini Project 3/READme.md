# Machine Learning Project: Classification and Visualization with SVM and LDA
This repository contains code for a machine learning project focused on classification and visualization using Support Vector Machines (SVM) with different kernels and Linear Discriminant Analysis (LDA). The project primarily works with the Iris dataset to classify iris flowers into different species.

## Overview
The project is divided into five main parts:

### Part 1: Data Preparation and Preprocessing
Objective: Download the Credit Card Fraud dataset from Kaggle, preprocess the data, perform scaling, oversampling using SMOTE, and prepare the dataset for further analysis.
Technologies: Python, pandas, scikit-learn, matplotlib, seaborn.
### Part 2: Exploratory Data Analysis and Visualization
Objective: Explore the features of the Iris dataset, visualize data distributions, correlations, and use t-SNE for dimensionality reduction.
Technologies: Python, pandas, matplotlib, seaborn, scikit-learn.
### Part 3: Classification with Linear SVC and LDA
Objective: Implement Linear Discriminant Analysis (LDA) for dimensionality reduction, train a Linear SVC model, and visualize the decision boundaries.
Technologies: Python, pandas, scikit-learn, matplotlib, seaborn.
### Part 4: Visualization of Polynomial SVC Decision Boundaries
Objective: Train Polynomial Support Vector Classifier (SVC) models with varying degrees, visualize decision boundaries using matplotlib, and create an animated GIF illustrating boundary changes.
Technologies: Python, pandas, scikit-learn, matplotlib, seaborn.
### Part 5: Custom Polynomial SVM Implementation from Scratch
Objective: Implement a custom Polynomial SVM using numpy, including polynomial kernel computation, model training with SMO optimization, and visualization of decision boundaries.
Technologies: Python, numpy, matplotlib, scikit-learn.

Dependencies: Required Python libraries are listed in requirements.txt. Install dependencies using pip install -r requirements.txt.
Instructions
Clone the repository and navigate to the project directory.
Install dependencies using pip install -r requirements.txt.
Run each part's Jupyter notebook or Python script sequentially to reproduce the results.
### Results and Visualizations
Each part provides visualizations and evaluation metrics such as accuracy, F1-score, and confusion matrices.
Animated GIFs (SVM_Decision_Boundary.gif, SVM_Scratch_decision_boundaries.gif) demonstrate dynamic changes in decision boundaries across different models and polynomial degrees.
### Conclusion
This project showcases the application of SVMs with various kernels and LDA for classification tasks using the Iris dataset. It also includes a custom implementation of Polynomial SVM from scratch, offering insights into SVM internals and optimization techniques.
