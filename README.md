<h1 align='center'> CLUSTERING-METHODS-COMPARISON</h1>

<h2>INTRODUCTION</h2>

Performing clustering methods is a common technique used in data analysis to group similar data points together based on their similarity or distance metrics. KMeans clustering and Agglomerative Hierarchical clustering are two popular clustering methods that are frequently used in various fields of study.

KMeans clustering is a partitioning-based algorithm that partitions a given data set into a predetermined number of clusters, based on the similarity of the data points in the set. The algorithm works by randomly initializing k centroids and assigning each data point to the nearest centroid. The centroid is then updated based on the mean of the assigned data points, and the process repeats until convergence is reached. KMeans clustering is computationally efficient and works well for large datasets.

Agglomerative Hierarchical clustering is a bottom-up approach that builds a hierarchy of clusters by iteratively merging the closest pairs of data points or clusters based on a distance metric. The algorithm starts by treating each data point as a singleton cluster and then merges the closest pairs of clusters, based on a linkage criterion such as single linkage, complete linkage, or average linkage. The process continues until all data points belong to a single cluster or the desired number of clusters is reached. Agglomerative Hierarchical clustering is more computationally intensive than KMeans clustering but allows for more flexible and interpretable cluster structures.

<h2> OBJECTIVES </h2>

**Perform Clustering Methods**

**- KMeans Clustering**

**- Agglomerative Hierarchical clustering**

**- Compare both clustering methods**

<h2> CONCLUSION </h2>

n terms of comparison, KMeans clustering is suitable for datasets with a large number of features and a fixed number of clusters, whereas Agglomerative Hierarchical clustering is suitable for datasets with a small number of features and an unknown number of clusters. KMeans clustering is more scalable and computationally efficient than Agglomerative Hierarchical clustering but is sensitive to the initial random centroid placement. Agglomerative Hierarchical clustering is more flexible and allows for a hierarchical representation of the data, but is more computationally expensive and can be difficult to interpret for large datasets.
