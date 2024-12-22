# Customer-Segmentation

Understanding a company's varied customer base requires a thorough understanding of customer segmentation. Businesses can customize marketing strategies, product offerings, and customer experiences to each segment's unique demands by combining customers with comparable traits. Purchase history, age, location, frequency of purchases, and preferences are all used in this study to find trends. Techniques like grouping clients using clustering algorithms or automatically building personas to represent each segment may be used. The insights that emerge can direct customer retention tactics and tailored marketing efforts. 

**import**

pandas

numpy

seaborn

matplotlib

**Model**

![image](https://github.com/user-attachments/assets/f1a25037-df0d-47e7-bf2c-9d6c2a2a4fc3)

**Algorithms used**

1.Kmeans

K-means clustering is an algorithm which is used to perform the mall basket analysis which comes under the category Unsupervised learning.The main agenda is to companies need the customer data to know the better feature of the customer.By the K-means clustering customer segmentations will helps in figuring out the consumers who differ in the terms of expectations, desires, attributes and preferences. The important use of customer segmentation is to be grouping the customers with similar interests and needs which helps the marketing team to implement effective marketing strategy plan.

2.Hierarchical

Hierarchicalclustering is a method of clustering analysis that groups similar objects into clusters based on their similarities and differences. The two main types of hierarchical clustering are agglomerative clustering and divisive clustering. In agglomerative clustering, each data point is initially considered as a separate cluster, and then, at each iteration, the two closest clusters are merged together, until all the data points are grouped into a single cluster. In divisive clustering, all the data points are initially grouped into a single cluster, and then, at each iteration, the cluster is split into two smaller clusters, until each data point is in a separate cluster

3.DbScan

Density-based clustering is a clustering technique that groups together data points based on their density in a high-dimensional space,It is commonly used to identify clusters of arbitrary shape in a dataset and is particularly useful when the clusters have varying densities or are separated by noisy or sparse regions.. One of the most popular density-based clustering algorithms is DBSCAN DBSCAN works by defining two parameters: epsilon (ε) and minimum number of points (minPts). The algorithm first identifies "core" points that have at least minPts points within a distance of ε. These core points form the center of a cluster, and any points within ε distance of them are added to the same cluster. Points that are not core points and are not within ε distance of any core points are considered noise points. Another density-based clustering algorithm is OPTICS 
