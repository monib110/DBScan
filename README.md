# DBScan

DBSCAN clustering is an underrated yet super useful clustering algorithm for unsupervised learning problems.
DBSCAN can find non-linearly separable clusters.

It groups ‘densely grouped’ data points into a single cluster.
It can identify clusters in large spatial datasets by looking at the local density of the data points.
The most exciting feature of DBSCAN clustering is that it is robust to outliers.
It also does not require the number of clusters to be told beforehand, unlike K-Means, where we have to specify the number of centroids.

DBSCAN requires only two parameters: epsilon and minPoints.
Epsilon is the radius of the circle to be created around each data point to check the density
and minPoints is the minimum number of data points required inside that circle for that data point
to be classified as a Core point.
