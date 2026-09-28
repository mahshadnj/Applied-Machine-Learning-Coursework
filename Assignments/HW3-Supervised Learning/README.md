# Homework 3 — Supervised Learning

This assignment explores several supervised learning algorithms,
including K-Nearest Neighbors, Decision Trees, Random Forests,
Naive Bayes, Logistic Regression, and Principal Component Analysis.

## Q1 — KNN Classification on Social Network Ads

Build a K-Nearest Neighbors classifier using the `Age` and
`EstimatedSalary` features from the Social Network Ads dataset.

Main tasks:
- Standardize the numerical features
- Split the data into training and test sets
- Determine the optimal value of `K` using 5-fold cross-validation
- Plot validation accuracy versus `K`
- Train the final KNN classifier
- Evaluate the model using accuracy and a confusion matrix
- Visualize the two-dimensional decision boundary

Notebook: `Q1-knn-social-network-ads.ipynb`

---

## Q2 — Decision Tree and Random Forest on Titanic

Compare Decision Tree and Random Forest classifiers on the Titanic
dataset.

Main tasks:
- Preprocess numerical and categorical variables
- Handle missing values
- Apply one-hot encoding
- Tune Decision Tree hyperparameters using 5-fold cross-validation
- Tune Random Forest hyperparameters
- Evaluate both models using accuracy and confusion matrices
- Extract and compare the five most important features

Notebook: `Q2-decision-tree-random-forest-titanic.ipynb`

---

## Q3 — Naive Bayes and Logistic Regression on Digits

Compare Gaussian Naive Bayes and multinomial Logistic Regression
on the scikit-learn Digits dataset.

Main tasks:
- Train both models on the original 64-dimensional feature space
- Tune the regularization parameter of Logistic Regression
- Apply PCA while preserving 95% of the variance
- Retrain both models using PCA-reduced features
- Compare accuracy and confusion matrices before and after PCA
- Analyze the effect of dimensionality reduction on model performance

Notebook: `Q3-naive-bayes-logistic-regression-digits.ipynb`
