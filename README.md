### K-means Clustering

K-means is a popular clustering algorithm used for partitioning data into K clusters based on similarity. The implementation provided in this repository follows the traditional K-means algorithm, including the initialization of centroids, assignment of data points to clusters, and update of centroids until convergence.


######Example 
#usage of K-means clustering

from k_means import KMeans

#Instantiate KMeans class

kmeans = KMeans(n_clusters=3)

#Fit the model to data

kmeans.fit(X)

#Get cluster centroids

centroids = kmeans.centroids

#Get cluster assignments for data points

labels = kmeans.labels
