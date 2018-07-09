# k-Means++
This is my implementation of the K-Means++ machine learning clustering algorithm, an optimized version of K-Means
* It is written in Matlab and uses the data from https://archive.ics.uci.edu/ml/datasets/Iris to cluster different species of Iris flowers. 
* It changes the way the initial centroids are randomly chosen
* It increases the weights(probability) of a possible inital centroid to be chosen in proportion to its distance from already selected centroid
* The weights are then normalized by averaging the distance from the number of remaining unchosen possible centroids
* This takes advantage of the fact that clusters tend to be farther away from each other
* It has the ability to change the number of K clusters and the ability to change the number of iterations ran. 
* In the end of all the iterations, it calculates the Sum of Squared Errors so I have an indication of goodness in my clustering. 
* I then can use this data to graph a knee plot which gives me a good visualization of how many clusters there truly is. 
