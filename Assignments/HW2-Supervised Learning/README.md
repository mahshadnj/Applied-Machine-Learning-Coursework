# Homework 2 — Supervised Learning

This assignment explores supervised machine learning workflows,
including preprocessing, model pipelines, hyperparameter tuning,
cross-validation, regularization, dimensionality reduction, and
classification/regression evaluation.

## Q1 — Titanic Binary Classification with RBF-SVM

Build a binary classification pipeline using the Titanic dataset.

Main tasks:
- Load and inspect the dataset
- Handle numerical and categorical features
- Impute missing values
- Apply feature scaling and one-hot encoding
- Build an RBF-SVM classifier
- Tune `C` and `gamma` using GridSearchCV
- Evaluate the final model using Accuracy, F1-score, ROC-AUC,
  and a confusion matrix

Notebook: `Q1-titanic-svm.ipynb`

---

## Q2 — California Housing Regression with Ridge Regression

Investigate the effect of polynomial model complexity and
regularization on the California Housing dataset.

Main tasks:
- Generate polynomial features with degrees 1, 2, and 3
- Standardize the features
- Fit Ridge Regression models
- Tune the regularization parameter `alpha`
- Compare models using test MSE and R²
- Study overfitting and generalization

Notebook: `Q2-california-housing-ridge.ipynb`

---

## Q3 — Multiclass SVM Classification on the Iris Dataset

Compare linear and nonlinear SVM classifiers on the Iris dataset.

Main tasks:
- Train a baseline linear SVM
- Standardize input features
- Reduce dimensionality using PCA
- Train an RBF-SVM in the PCA space
- Tune hyperparameters using GridSearchCV
- Compare model performance
- Visualize the decision regions in two-dimensional PCA space

Notebook: `Q3-iris-svm-pca.ipynb`
