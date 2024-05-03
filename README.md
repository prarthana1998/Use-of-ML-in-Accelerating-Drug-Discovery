# Use-of-ML-in-Accelerating-Drug-Discovery
## Aims and Objectives

The primary aim of the research project is to use machine learning models to predict the pIC50 values of acetylcholinesterase inhibitors. This predictive analysis will provide valuable insights into the potency of these inhibitors. By leveraging the prediction results, the project aspires to contribute to the comprehensive evaluation of drug candidates, enabling an informed assessment of the possibility of a compound to be considered as a viable therapeutic candidate.

As a result, the research has a number of key objectives that it aims to accomplish, including the following:

- To explore the chemical landscape of AChE inhibitors
- To implement and evaluate various machine learning models for drug likeness prediction
- To investigate the relative contributions of the molecular descriptors in predicting drug likeness for AChE inhibitors.

## Methodology Overview

### 1. Data Collection and Preprocessing:
- Obtained AChE inhibitors dataset from Chembl 20 database.
- Removed compounds without IC50 values and duplicates.
- Conducted class binning for IC50 value categorization.
- Transformed IC50 to pIC50 for standardization.

### 2. QSAR Modelling:
- Constructed QSAR models using machine learning.
- Calculated Lipinski descriptors for drug-likeness evaluation.
- Conducted feature extraction and selection.
- Split dataset into training and testing subsets (80-20 split).
- Performed hyperparameter tuning with GridSearchCV.

### 3. Regression Models:
- Employed Random Forest, XGBoost, SVR, and KNN regression models.
- Tuned hyperparameters for optimal performance.

### 4. Model Evaluation:
- Utilized metrics such as MSE, RMSE, R-squared, MAE, and Cross-Validation score for evaluation.

This methodology aimed to accelerate drug discovery by predicting compound bioactivity using machine learning techniques.

Full dissertation can be found here https://drive.google.com/file/d/19iWYSXAh3r0kyYpBC3zv6URilXaG2N81/view?usp=sharing and the recording explaining the same can be found here 

