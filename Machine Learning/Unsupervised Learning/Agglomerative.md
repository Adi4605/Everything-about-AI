A "bottom-up" hierarchical clustering method.

Starts with each data point as its own cluster, then iteratively merges the two closest clusters until only one large cluster remains, forming a hierarchy often visualized with a dendrogram.

It uses distance metrics (like Euclidean) and linkage criteria (like single, complete, Ward) to determine similarity, allowing for flexible cluster numbers and easy visualization of data relationships without pre-specifying k.

Working:
**1. Start with all points separate:**
- Treat each data point as its own cluster like A, B, C, ...
- Initially, you have n clusters for n data points.
**2. Compute pairwise distances:**
- Calculate the distance between every pair of clusters.
- Common choices include Euclidean, Manhattan or Cosine distance.
- Store these values in a distance matrix.
**3. Merge the nearest clusters:**
- Identify the two clusters that are closest based on the chosen linkage method such as single, complete, average or Ward linkage.
- Combine them into a single new cluster.
**4. Update distances:**
- Recalculate the distances between the newly formed cluster and all remaining clusters.
- Use the same linkage rule to ensure consistency.
**5. Repeat the process:**
- Continue merging clusters and updating distances iteratively.
- Stop when you reach a predefined number of clusters (k) or a distance threshold.
**6. Visualize the results:**
- Create a dendrogram to visualize how clusters merged at each step.
- Choose a suitable cut on the [[Dendrogram]] to obtain the final cluster groups.
![[Pasted image 20260101110650.png]]
