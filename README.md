# Machine Learning Projects

## Overview

This repository contains a collection of machine learning projects based on datasets from various datasets. The main objective is to analyze and visualize the data, explore patterns and correlations, and then proceed to the use of predictive models, analyzing them and identifying the best ones.

## Projects

### Pricing Boston House Analysis

This project began as an exploratory data analysis (EDA) exercise, focusing on the visualization of the dataset's features, the search for correlations, and possible interpretations. One of the most notable correlations found was between TAX (property tax rate) and RAD (index of accessibility to radial highways).
Subsequently, I applied three regression models—Linear Regression, Decision Tree, and Support Vector Machine (SVM)—to predict housing prices. Model performance was evaluated using MSE, RMSE, R², and MAPE, with the Decision Tree model achieving the best results.
To further improve the model, I applied the Variance Inflation Factor (VIF) to identify and address potential multicollinearity among the features, removing redundant variables. As a result, NOX and TAX were excluded. After retraining the Decision Tree model on the reduced dataset, the results remained nearly unchanged.

### Iris Dataset Analysis

This project includes an analysis of the Iris flower dataset, focusing on the distribution of species and their morphological characteristics. Iris Setosa was found to be notably distinct from the other two species. Outlier detection and removal were also performed despite the dataset’s small size.
Three classification models—K-Nearest Neighbors, Support Vector Machine, and Decision Tree—were implemented to predict flower species. Model performance was assessed using accuracy, precision, recall, and confusion matrix. Among them, the Decision Tree model achieved the highest performance.

## Author

[Daniele Notarangelo](https://github.com/danielenotarangelo)

## License

This project is licensed under the MIT License.
