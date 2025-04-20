# SVM_Parameter_Optimization
This repository showcases the implementation of SVM optimization on the UCI Wine Quality dataset using a Jupyter notebook.

## Project Objectives
Selected a multi-class dataset from the UCI library containing between 5,000 and 30,000 rows

- Split the dataset into 70% training and 30% testing
- Generated 10 distinct training samples
- Applied SVM optimization on each sample over 100 iterations
- Logged the highest accuracy and corresponding hyperparameters for each sample
- Plotted a convergence graph for the best-performing model

## Dataset Information
- Dataset: UCI Wine Quality (White Wine)
- Size: 4,898 samples, 11 input features, and 1 output label (quality)
- Task: Multi-class classification (quality scores ranging from 3 to 9)

## Results
### Accuracy Comparison Table
The table below highlights the optimized SVM performance across the 10 training samples:

<img src="https://github.com/Archit-29/SVM_Parameter_Optimization/blob/main/Screenshot%202025-04-19%20221213.png" alt="Performance Table" />
Best Model Convergence
Below is the convergence graph for the highest-performing SVM model:
<img src="https://github.com/Archit-29/SVM_Parameter_Optimization/blob/main/42d6c5ba.png" alt="Convergence Graph" />

## Implementation Summary
The notebook includes:
- Data cleaning, preprocessing, and normalization
- SVM hyperparameter tuning using GridSearchCV
- Evaluation of model performance using accuracy scores
- Visualization of comparison metrics and convergence behavior
