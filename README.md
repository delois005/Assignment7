# Assignment 7: Clustering Analysis

## Overview

This project explores unsupervised learning techniques using the Wine Clustering dataset. The analysis applies Principal Component Analysis (PCA) to reduce dimensionality, followed by K-Means clustering and Hierarchical Clustering to identify natural groupings within the data.

The assignment also includes responses to Conceptual Question #1 and Applied Question #9 from *An Introduction to Statistical Learning (ISLR) Python Edition*.

## Objectives

- Perform Principal Component Analysis (PCA)
- Retain at least 80% of the dataset variance
- Evaluate multiple values of k using K-Means clustering
- Identify an appropriate number of clusters using the elbow method
- Perform Hierarchical Clustering using complete linkage
- Investigate assumptions of PCA, K-Means, and Hierarchical Clustering
- Interpret clustering results and compare methods

## Dataset

**Wine Clustering Dataset**

- Source: Kaggle
- Observations: 178 wines
- Variables: 13 chemical attributes

## Methods

### Principal Component Analysis (PCA)

The original 13 variables were standardized and reduced to 5 principal components, preserving approximately 80% of the total variance.

### K-Means Clustering

Multiple cluster solutions (k = 2 through k = 10) were evaluated using the elbow method. A three-cluster solution was selected based on the observed reduction in inertia.

### Hierarchical Clustering

Hierarchical clustering was performed using:

- Complete linkage
- Euclidean distance

A dendrogram was used to visualize cluster formation and evaluate group structure.

## Results

- PCA reduced the dataset from 13 variables to 5 principal components.
- Five principal components retained approximately 80% of the total variance.
- The elbow method suggested that k = 3 provided a reasonable clustering solution.
- K-Means identified three distinct and relatively balanced clusters.
- Hierarchical clustering produced a similar grouping structure, supporting the K-Means results.

## Files

- `Assignment7.ipynb` – Complete Jupyter notebook containing all code, visualizations, and interpretations.
- `Assignment7 - JupyterLab.pdf` – PDF export of the completed notebook for easy review.
- `wine-clustering.csv` – Wine Clustering dataset used for PCA and clustering analyses.
- `README.md` – Project documentation and summary of methods, results, and references.

## References

Abdulhafedh, A. (2021). Incorporating K-means, hierarchical clustering and PCA in customer segmentation. *Journal of City and Development, 3*(1), 12–30. https://doi.org/10.12691/jcd-3-1-3

Buscemi, S., Grosso, G., Vasto, S., Galvano, F., & Marventano, S. (2023). The application of clustering on principal components for nutritional epidemiology: A workflow combining PCA, hierarchical clustering, and k-means. *Nutrients, 15*(1), Article 195. https://doi.org/10.3390/nu15010195

Ding, C., & He, X. (2004). K-means clustering via principal component analysis. In *Proceedings of the Twenty-First International Conference on Machine Learning* (pp. 29–36). ACM. https://doi.org/10.1145/1015330.1015408

## Author

Delois Sistrunk

Course: [Course Name]

Semester: [Term]
