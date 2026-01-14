# Logistic Regression L2 Regularization Analysis

This repository contains a Jupyter Notebook that demonstrates the effects of L2 regularization on a Logistic Regression classifier using the Scikit-learn digits dataset.

## Project Overview
The goal of this project is to visualize how varying the regularization strength ($C$) affects model performance and decision boundaries. 

### Key Features:
* **Dataset:** Scikit-learn digits dataset (8x8 images of hand-written digits).
* **Model:** Logistic Regression with L2 penalty.
* **Visualizations:**
    * Meshgrid plots for decision boundary visualization.
    * Semilog plots of Training vs. Validation error rates across different $C$ values.
* **Hyperparameter Tuning:** Evaluation of $C$ values ranging from 0.001 to 1000.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Joe-Naz01/logistic_reg.git
   cd logistic_reg
   pip install requirements.txt
