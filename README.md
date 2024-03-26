# Model Selection

This repository contains code for performing model selection techniques such as Grid Search and k-Fold Cross Validation on a Support Vector Machine (SVM) classifier using the scikit-learn library in Python. The dataset used is the "Social_Network_Ads.csv" which contains information about the age, estimated salary, and whether the person purchased a subscription or not.

## Dataset

The "Social_Network_Ads.csv" dataset consists of the following features:

- Age: The age of the person
- Estimated Salary: The estimated salary of the person
- Purchased: Whether the person purchased a subscription or not (0 for no, 1 for yes)

## Grid Search

The `grid_search.py` file contains code for performing Grid Search on the SVM classifier. Grid Search is a technique that exhaustively searches for the best combination of hyperparameters for a given model. In this code, Grid Search is used to find the optimal values for the `C` (regularization parameter) and `gamma` (kernel coefficient) hyperparameters of the SVM classifier.

## k-Fold Cross Validation

The `cross_validation.py` file contains code for performing k-Fold Cross Validation on the SVM classifier. Cross Validation is a technique used to evaluate the performance of a machine learning model on unseen data. In k-Fold Cross Validation, the dataset is split into k subsets, and the model is trained and evaluated k times, with each subset used exactly once for evaluation.

## Visualization

Both scripts include code for visualizing the decision boundary of the trained SVM classifier on the training and test sets using matplotlib.

## Usage

1. Clone this repository to your local machine.
2. Ensure that you have Python and the required libraries (numpy, pandas, matplotlib, scikit-learn) installed.
3. Navigate to the project directory.
4. Run the `grid_search.py` file to perform Grid Search and view the best hyperparameters and accuracy.
5. Run the `cross_validation.py` file to perform k-Fold Cross Validation and view the mean accuracy and standard deviation.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
