# Kmeans_exercise-
<!-- This Markdown document introduces and explains the K-means clustering code using scikit-learn. K-means clustering is a popular unsupervised machine learning technique used for clustering data into K distinct groups. -->

## Introduction

This Python script demonstrates the implementation of the K-means clustering algorithm using scikit-learn. K-means clustering is a popular unsupervised machine learning technique used for clustering data into K distinct groups.

### Libraries Used
- `numpy`: For numerical computations.
- `pandas`: For data manipulation (not used in this script but often used in data science projects).
- `matplotlib`: For data visualization.
- `sklearn.datasets.make_blobs`: For generating random sample data.
- `sklearn.cluster.KMeans`: For performing K-means clustering.

### Steps in the Code

1. **Generate Random Sample Data**: Random data with 300 samples, 4 centers, and a standard deviation of 0.60 is generated using `make_blobs`.
2. **Visualize the Generated Data**: The generated data is visualized using scatter plots to understand its distribution.
3. **Apply K-means Clustering**: The K-means clustering algorithm with 4 clusters is applied to the data.
4. **Visualize Clusters and Centroids**: The clustered data and centroids determined by K-means are visualized using scatter plots.

Let's walk through the code to understand each step in detail.
