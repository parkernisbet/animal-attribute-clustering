# Animal Attribute Clustering
A quick comparison of two clustering methods for text-based animal species classification. This dataset relies on a class / attribute table for grouping together various animal species, pulled from [here](https://cvml.ist.ac.at/AwA/). With no performance metrics to speak of, my commentary within the .ipynb file is mostly on the quality of the output of each clustering method. Both methods were logical enough in terms of placing together mostly similar animal species, with only a few slightly suspect pairings in the K-Means clusters (more on this inside the .ipynb file). The hierarchical cluster, by way of generated dendrogram visualization, one-upped by providing a bit more insight as to what animals were more closely related.

The K-Means method was given an arbitrary value of k = 10 to start, and then tested from 1 to 10 to find the optimal k value (right around 4). When directly comparing the two clustering methods at k = 3, the only notable difference was K-Means instead classifiying "beavers" in a group entirely different from the "aquatic" animals cluster.
