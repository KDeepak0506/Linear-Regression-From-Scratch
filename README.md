Linear Regression from Scratch in Python

This project demonstrates how I built a Linear Regression model from scratch, without using any machine learning libraries like Scikit-learn for training. The goal was to understand how gradient descent, cost functions, and predictions really work under the hood.

What this project includes

- Manual implementation of the linear regression algorithm
- Custom gradient descent optimizer
- Mean Squared Error (MSE) loss calculation
- Visual comparison of predictions from my model and Scikit-learn's model
- Tested on two real datasets: Housing and Advertising

Datasets used

1. Housing.csv  
   - Feature: Area of house  
   - Target: Price  

2. advertising.csv  
   - Feature: TV advertisement budget  
   - Target: Sales  

Results and Accuracy

For Dataset 1 (Housing)

- Scikit-learn MSE: 0.0187  
- My Model MSE: 0.0213  

For Dataset 2 (Advertising)

- Scikit-learn MSE: 0.0081  
- My Model MSE: 0.0091  

These results show that my hand-coded model achieves accuracy very close to Scikit-learn’s implementation.

Project files

- Housing.csv - Dataset for house prices
- advertising.csv - Dataset for TV ad budgets and sales
- Linear_Regression_without_sklearn.ipynb - Main Jupyter notebook with all code
- Linear_Regression_without_sklearn.py - Main file in Python
- README.md - Project overview

What I learned

- How to implement gradient descent from scratch
- Why feature normalization matters
- How to visualize training progress and predictions
- The value of comparing custom models to existing ones