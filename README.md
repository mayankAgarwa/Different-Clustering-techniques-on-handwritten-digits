K-means clustering is a classical clustering algorithm that uses an expectation maximization like technique to partition a number of data points into k clusters. K-means clustering is commonly used for a number of classification applications. Because k-means is run on such large data sets, and because of certain characteristics of the algorithm, it is a good candidate for parallelization.

Termination Condition: When the clusters converge,i.e. centroids doesnt change in two consecutive steps.

Final Clusters thus recieved are visualized in jupyter notebook. The final clusters achieved by training on full MNIST data set was 10, as expected. The final clusters are converted into 28*28 pixel format, and forms digit like figures.
