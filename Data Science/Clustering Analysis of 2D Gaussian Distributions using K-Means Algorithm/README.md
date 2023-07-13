In this project, the goal was to apply the k-means algorithm to a dataset generated from two different 2D Gaussian distributions. The dataset was created by sampling 10,000 points from each Gaussian distribution and combining them. The algorithm was then applied to the combined dataset to cluster the points.

To determine the optimal number of clusters (k), two different seed selection strategies were employed: the elbow method and the average silhouette method. The elbow method involved plotting the distortion score as a function of the number of clusters and selecting the k value at the "elbow" of the curve. The average silhouette method calculated silhouette scores for different k values and chose the one with the highest score.

The progress of the k-means algorithm was visualized at each iteration, showing the movement of the centroids. Additionally, the process was repeated with different random initial seeds to observe the effect on the clustering results.

Furthermore, the study explored the impact of varying the parameters of the Gaussian distributions (mean and variance) on the clustering results. It was found that regardless of changes in the mean and standard deviation, the optimal number of clusters remained the same.

<img width="358" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/b5ed7fe6-4813-4976-8bc9-00aad60ca582">

