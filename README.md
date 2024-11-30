# ML-Assignment-4

# Clustering Algorithm 

Objective:
The objective of this assessment is to evaluate your understanding and ability to apply clustering techniques to a real-world dataset.

Dataset
Use the Iris dataset available in the sklearn library.

Key components to be fulfilled :

1. Loading and Preprocessing (1 marks)
Load the Iris dataset from sklearn.
Drop the species column since this is a clustering problem.

2.Clustering Algorithm Implementation (8 marks)
Implement the following two clustering algorithms:
A) KMeans Clustering (4 marks)
Provide a brief description of how KMeans clustering works.
Explain why KMeans clustering might be suitable for the Iris dataset.
Apply KMeans clustering to the preprocessed Iris dataset and visualize the clusters.
B) Hierarchical Clustering (4 marks)
Provide a brief description of how Hierarchical clustering works.
Explain why Hierarchical clustering might be suitable for the Iris dataset.
Apply Hierarchical clustering to the preprocessed Iris dataset and visualize the clusters.

3.Timely Submission (1 mark)

Submission Guidelines
Provide your code in a Jupyter Notebook format and submit the GitHub link here.
Ensure your explanations and answers are clear and concise.
Total Score: 10


# 1. Loading and Preprocessing (1 mark)
Steps:
Import necessary libraries (pandas, numpy, matplotlib, seaborn, and sklearn modules).
Load the Iris dataset using datasets.load_iris() from sklearn.
Convert the dataset into a DataFrame using pandas.
Drop the species column since it's a clustering problem (unsupervised).

# 2. Clustering Algorithm Implementation (8 marks)
(A) KMeans Clustering (4 marks)

Brief Description:
------------------
KMeans clustering is an iterative algorithm that partitions data into k clusters based on minimizing intra-cluster distances.
Each cluster is represented by its centroid, and data points are assigned to the nearest centroid.

Suitability for Iris Dataset:
-----------------------------
The Iris dataset consists of numeric data with distinct groupings, making it ideal for KMeans clustering.

Implementation:
---------------
Use sklearn.cluster.KMeans.
Fit the model on the preprocessed data.
Visualize clusters using a scatter plot.

# (B) Hierarchical Clustering (4 marks)

Brief Description:
------------------
Hierarchical clustering builds a hierarchy of clusters by either a bottom-up approach (agglomerative) or a top-down approach (divisive).
Data points are grouped based on their distance.

Suitability for Iris Dataset:
-----------------------------
The small size and clear separability of the Iris dataset make it suitable for hierarchical clustering.

Implementation:
---------------
Use scipy.cluster.hierarchy for agglomerative clustering.
Create dendrograms and visualize the clusters.
