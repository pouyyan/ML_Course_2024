# Classification and Visualization with SVM and LDA
This repository contains Python code focused on classification and visualization using Support Vector Machines (SVM) with different kernels and Linear Discriminant Analysis (LDA). The project primarily works with the Iris dataset to classify iris flowers into different species.

## Links
||Google Drive <br />(including the <br /> LaTeX report file)|Google Colab|
|---|---|---|
| Links | [![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1iSWpBIzpoc3nQW1oToOOuWCDi3Fsg8St?usp=sharing) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1BgLTugGfm8VVp9qcLZz0LbvJF7-DidIe?usp=sharing) |

## Requirements
To run the code, ensure you have the following installed:

Python 3.x

Jupyter Notebook (for running interactively)

## Setup

Run Jupyter Notebook or any Python environment that supports interactive sessions.

## Overview
The code is divided into five main parts:
### Part 1: Data Preparation and Preprocessing
Objective: Download the Credit Card Fraud dataset from Kaggle, preprocess the data, perform scaling, oversampling using SMOTE, and prepare the dataset for further analysis.
Libraries: Python, pandas, scikit-learn, matplotlib, seaborn.
### Part 2: Exploratory Data Analysis and Visualization
Objective: Explore the features of the Iris dataset, visualize data distributions, correlations, and use t-SNE for dimensionality reduction.
Libraries: Python, pandas, matplotlib, seaborn, scikit-learn.
### Part 3: Classification with Linear SVC and LDA
Objective: Implement Linear Discriminant Analysis (LDA) for dimensionality reduction, train a Linear SVC model, and visualize the decision boundaries.
Libraries: Python, pandas, scikit-learn, matplotlib, seaborn.
### Part 4: Visualization of Polynomial SVC Decision Boundaries
Objective: Train Polynomial Support Vector Classifier (SVC) models with varying degrees, visualize decision boundaries using matplotlib, and create an animated GIF illustrating boundary changes.
Libraries: Python, pandas, scikit-learn, matplotlib, seaborn.
### Part 5: Custom Polynomial SVM Implementation from Scratch
Objective: Implement a custom Polynomial SVM using numpy, including polynomial kernel computation, model training with SMO optimization, and visualization of decision boundaries.
Libraries: Python, numpy, matplotlib, scikit-learn.
### Results and Visualizations
Each part provides visualizations and evaluation metrics such as accuracy, F1-score, and confusion matrices.
Animated GIFs (SVM_Decision_Boundary.gif, SVM_Scratch_decision_boundaries.gif) demonstrate dynamic changes in decision boundaries across different models and polynomial degrees.
### Conclusion
This project showcases the application of SVMs with various kernels and LDA for classification tasks using the Iris dataset. It also includes a custom implementation of Polynomial SVM from scratch, offering insights into SVM internals and optimization techniques.

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
OpenAI Gym

Stable Baselines3

## License

This project is licensed under the MIT License - see the LICENSE file for details.
