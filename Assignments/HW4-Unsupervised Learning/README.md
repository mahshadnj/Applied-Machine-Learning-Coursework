# Homework 4 — Unsupervised Learning

This assignment focuses on dimensionality reduction and clustering
using PCA, K-Means, and Hierarchical Clustering.

## Q1 — Image Dimensionality Reduction with PCA

Apply Principal Component Analysis to reduce the dimensionality of
a color image while preserving at least 95% of its variance.

Main tasks:
- Load an image provided by the user
- Apply PCA-based dimensionality reduction
- Prevent dimensionality reduction below the 95% explained-variance threshold
- Reconstruct the compressed image
- Compare the original and reconstructed images
- Plot cumulative explained variance versus the number of components

Notebook: `Q1-image-dimensionality-reduction-pca.ipynb`

Input image: `data/sunflowers.jpg`

---

## Q2 — Country Clustering with K-Means

Cluster countries using economic and health indicators from the
`Country-data.csv` dataset.

Main tasks:
- Standardize the numerical features
- Determine the optimal number of clusters using the Elbow method
- Perform K-Means clustering
- Compare cluster-level feature statistics
- Interpret the resulting groups
- Visualize the clusters in two and three dimensions

Notebook: `Q2-kmeans-country-clustering.ipynb`

---

## Q3 — Hierarchical Clustering of Countries

Apply Hierarchical Agglomerative Clustering to the same country dataset.

Main tasks:
- Scale the input features
- Compare Single, Complete, and Average linkage methods
- Analyze cluster sizes and feature characteristics
- Generate and interpret dendrograms
- Compare Hierarchical Clustering with K-Means

Notebook: `Q3-hierarchical-country-clustering.ipynb`
