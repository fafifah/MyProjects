In this project, the goal was to apply the k-means algorithm to a dataset generated from two different 2D Gaussian distributions. The dataset was created by sampling 10,000 points from each Gaussian distribution and combining them. The algorithm was then applied to the combined dataset to cluster the points.

<img width="358" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/c824b73a-8509-4594-87b9-45fddb0ca6f2">

To determine the optimal number of clusters (k), two different seed selection strategies were employed: the elbow method and the average silhouette method. The elbow method involved plotting the distortion score as a function of the number of clusters and selecting the k value at the "elbow" of the curve. The average silhouette method calculated silhouette scores for different k values and chose the one with the highest score.

**Elbow method**

<img width="547" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/8774d18a-32d8-4f09-805a-d331004aa707">
<img width="351" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/5a034249-0ccd-476d-a3e3-13c0bd1a8e7d">

**Average silhouette method**

<img width="370" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/3caaafed-f180-4f74-8223-69e6536dd037">
<img width="493" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/02e87f06-c080-44e9-bd72-ec9a61ab75d7">

**Visualization of the progress of the K-Mean algorithm at each iteration**

The progress of the k-means algorithm was visualized at each iteration, showing the movement of the centroids. Additionally, the process was repeated with different random initial seeds to observe the effect on the clustering results.There is a total of 20 iteration figure. Only the first and last few iterations are shown here.

<img width="521" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/8cf9f843-caee-49db-babf-926de640732d">
<img width="518" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/6146470f-b649-46e9-b221-2f641f92dfba">
<img width="533" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/a293dac6-03f7-4ede-b5a1-ec59b34c4fcd">

**Experimenting with different seed**

<img width="508" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/0176960d-a74d-49a8-a87d-edfbbd28dba5">
<img width="508" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/1d3ba3e2-47a1-4419-80ba-c457a40c3986">


**what happens when the parameters of the Gaussian (mean and variance) are varied.**

The study explored the impact of varying the parameters of the Gaussian distributions (mean and variance) on the clustering results. It was found that regardless of changes in the mean and standard deviation, the optimal number of clusters remained the same.

<img width="416" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/3fcf0054-a0c3-423a-a04e-e637340dfcd6">
<img width="603" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/39311bef-fc59-437d-b0e0-070d90e00a7e">





