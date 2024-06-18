# Prediction-Using-Unsupervised-ML

# Objective:
 Finding the optimum number of clusters for k-means classification using the Elbow Method.

Elbow Method:
plots the within-cluster sum of squares (WCSS) against the number of clusters. The optimal number of clusters is identified at the "elbow" point where the rate of decrease of WCSS slows down significantly.

# Implementation Details:

The code utilizes KMeans from scikit-learn to fit models for various values of k.
The inertia_ attribute of KMeans provides the WCSS value for each model.
WCSS values for different values of k (ranging from 1 to 10 in this example) are stored in a list named wcss.
A plot is generated where the x-axis represents the number of clusters (k), and the y-axis represents the corresponding WCSS values.

# Visualizing the Clusters:
To visualize the clusters identified by k-means:
Data points are plotted and colored based on their assigned cluster labels.

The visualization helps understand how the data points are grouped into clusters based on their features.
