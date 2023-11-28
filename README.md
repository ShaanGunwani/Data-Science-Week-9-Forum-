# Data-Science-Week-9-Forum-

KMeans Clustering: KMeans is an iterative algorithm dividing data into clusters. Initially, K clusters are defined, and data points are assigned to the nearest of K randomly initialized centroids. Centroids are recalculated based on the assigned data points until convergence. This iterative process forms the clusters.
Results:
Silhouette Score: 0.5818972375239817
Davies-Bouldin Index: 0.6448641393738762
Rand Score: 0.97993200471804
Calinski and Harabasz Score: 584.9536309233761

Mean Shift Clustering
Results:
Silhouette Score: 0.6800825549093847
Davies-Bouldin Index: 0.398126654081169
Rand Score: 0.5583714437541352
Calinski and Harabasz Score: 497.8561003637067


Agglomerative Clustering: Agglomerative Clustering is hierarchical, initially assigning each observation to its own cluster. It merges clusters iteratively by combining the closest ones until there's one cluster with all observations. Proximity between clusters determines their merging.

Results:
Silhouette Score: 0.5782157637460459
Davies-Bouldin Index: 0.6522266467240291
Rand Score: 1.0
Calinski and Harabasz Score: 569.640103743222


Spectral Clustering: Spectral Clustering utilizes eigenvectors from a similarity matrix to cluster data. It reduces dimensions by computing eigenvectors from the similarity matrix, enabling traditional clustering methods (like KMeans) on the reduced dimensions.

-Results:

Silhouette Score: 0.5818972375239817
Davies-Bouldin Index: 0.6448641393738762
Rand Score: 0.97993200471804
Calinski and Harabasz Score: 584.9536309233761
