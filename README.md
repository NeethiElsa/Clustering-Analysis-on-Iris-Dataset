# Clustering-Analysis-on-Iris-Dataset
This project applies K-Means and Hierarchical Clustering to the Iris dataset to explore how clustering techniques can group similar data points. The dataset consists of four numerical features corresponding to different iris flower species.

## Clustering Techniques Used
# Kmeans Clustering Algorithm
K-Means Clustering is an Unsupervised Machine Learning algorithm, which groups the unlabeled dataset into different clusters.K means clustering, assigns data points to one of the K clusters depending on their distance from the center of the clusters. It starts by randomly assigning the clusters centroid in the space. Then each data point assign to one of the cluster based on its distance from centroid of the cluster. After assigning each point to one of the cluster, new cluster centroids are assigned. This process runs iteratively until it finds good cluster.
K-Means Clustering is suitable for this dataset because this dataset has numerical features and K-Means operates effectively on numerical data because it uses the Euclidean distance to measure similarity.

# Hierarchial Clustering Algorithm
Hierarchical clustering is a data analysis technique that groups data into clusters based on similar characteristics. It's an unsupervised machine learning algorithm that creates a tree-like structure of clusters.
Hierarchical cluster analysis helps find patterns and connections in datasets. Results are presented in a dendrogram diagram showing the distance relationships between clusters.

# Conclusion
KMeans and Hierarchical Clustering successfully identified 3 clusters in the Iris dataset.
The dendrogram provided insight into hierarchical relationships between data points.

