Hierarchical clustering builds a hierarchy of clusters by either a bottom-up (agglomerative) or top-down (divisive) approach:
1. [[Agglomerative]] : Starts with each data point as its own cluster and progressively merges the most similar clusters until all data points belong to one cluster.
2. [[Divisive]] : Starts with all data points in a single cluster and recursively splits the data into smaller clusters.
Uses [[Euclidean Distance]] Formula, for other types of data, you might use different distance measures such as [[Manhattan distance]], [[Cosine similarity]], or [[Jaccard similarity]] depending on the nature of the data.

Implementation of Hierarchical clustering
To implement Hierarchical Clustering on a dataset containing both Environmental Impact Factors (like CO₂ emissions and waste) and Socioeconomic Indicators (like GDP and population). 
• Load Dataset 
• Preprocess the Data 
• Hierarchical Clustering 
• Fit the Model and Create [[Dendrogram]] 
• Apply [[Agglomerative]] Clustering 
• Evaluate the Clustering 
• Visualizing the Clusters