# Predictive Analysis

This repository contains the analysis, code, and results from the project "Predictive Dunking: Machine Learning Insights into Biscuits Softening Dynamics in Tea." The project explores the structural properties of biscuits and their interactions with tea during the dunking process using machine learning techniques and optimization methods.

Project Overview
The aim of the project is to:

Classify biscuit types using machine learning algorithms such as Random Forest and Support Vector Machines (SVM).
Analyze pore radius differences between biscuit types using microscopy data.
Evaluate the Washburn equation's accuracy and compare its performance with ML regressors.
Optimize predictive models for time-resolved datasets to improve prediction accuracy of tea absorption dynamics.
The project demonstrates how machine learning and traditional physical models can be used to gain insights into complex phenomena, with implications for both food science and manufacturing.

## Datasets
1. Dunking Dataset
Parameters: gamma (surface tension), phi (contact angle), eta (viscosity), L (distance), t (time), and biscuit type.
Purpose: To classify biscuit types (Rich Tea, Digestive, Hobnob) based on structural characteristics.
2. Microscopy Data
Focus: Examines pore radius of different biscuit types.
Purpose: Provides structural insights into biscuit morphology.
3. Time-Resolved Data (TR)
Variants: tr-1, tr-2, tr-3
Data: Length of tea absorption over time with controlled parameters (gamma, phi, eta).
Purpose: Evaluate predictive models and optimize parameters for the Washburn equation.

## Methodology
Machine Learning Techniques
Biscuit Classification

Algorithms: Random Forest, Support Vector Machine (SVM) with kernel comparison.
Metrics: Accuracy, Precision, Recall, F1-Score.
Pore Radius Analysis

Visualization of differences in pore radius between biscuit types.
Statistical analysis of pore radius data.
Regression for Tea Absorption

Models: Random Forest Regressor vs. Washburn equation.
Metrics: Mean Squared Error (MSE), R-squared (R²).
Model Optimization
Basin-Hopping Algorithm: Used to optimize Washburn equation parameters for better predictions on time-resolved datasets.


## Results
Biscuit Classification:

SVM (RBF kernel) achieved the highest accuracy: 86%.
Random Forest accuracy: 81.3%.
RBF kernel demonstrated superior generalization capability compared to other SVM kernels.
Regression Analysis:

Washburn equation outperformed Random Forest Regressor in predicting tea absorption length:
Lower MSE.
Higher R².
Pore Radius Analysis:

Type 3 biscuits exhibited larger average pore radii compared to Types 1 and 2.
Optimized Models:

Enhanced predictive accuracy for time-resolved datasets using parameter optimization techniques.


## Technologies Used
Programming Language: Python
Libraries and Tools:
Data Analysis: pandas, numpy
Visualization: matplotlib
Machine Learning: scikit-learn
Optimization: scipy.optimize


