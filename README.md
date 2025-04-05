# Logistic Regression Case Study - Completed Solutions

This directory contains the completed solutions for the Logistic Regression Advanced Case Study.

## Files

- `Logistic Regression Advanced Case Study.ipynb`: The original Jupyter notebook with the case study
- `heart.xlsx`: The heart disease dataset used in the case study

## Visualizations

- `bp_vs_cholesterol.png`: Scatter plot from Exercise Set I
- `c_parameter_search.png`: Parameter search plot from Exercise Set II
- `confusion_matrix.png`: Confusion matrix from Exercise Set III
- `gridsearch_confusion_matrix.png`: Confusion matrix from Exercise Set IV
- `gridsearch_c_parameter.png`: Parameter search plot from Exercise Set IV

## Exercise Set I
Created a scatter plot of Blood Pressure vs. Cholesterol Level with points colored by heart disease status.

## Exercise Set II
Implemented a search procedure to find the optimal C parameter for the logistic regression model.
- Best C value: 1.0
- Best cross-validation score: 0.8613

## Exercise Set III
Trained a logistic regression model with the optimal C parameter and evaluated its performance.
- Training accuracy: 0.9010
- Test accuracy: 0.8088
- Discussed the importance of cross-validation and grid search

## Exercise Set IV
Used scikit-learn's GridSearchCV to perform hyperparameter search in a more automated way.
- Best C value: 0.1
- Best cross-validation score: 0.8612
- Test accuracy: 0.8088
- Compared results with manual implementation

## Conclusion
Both the manual grid search and GridSearchCV approaches found similar optimal C values and achieved the same test accuracy. The GridSearchCV approach is more concise and offers additional benefits like parallel processing and easy extension to multiple hyperparameters.
