Evaluates how well-separated and dense your clusters are.

Ranging from -1 to +1:
	**+1 (Excellent):** Data point is far from neighboring clusters, well within its own cluster. 
	**~0 (Indifferent):** Data point is close to the decision boundary between two clusters; clusters are overlapping. 
	**-1 (Poor):** Data point is closer to another cluster than its own; likely misclassified.

It balances intra-cluster cohesion (compactness) and inter-cluster separation, helping to find the optimal number of clusters by assessing cluster quality.

Formula = ![[Pasted image 20260101112209.png]]

where: 
• a(i) is the average distance between point i and all other points in the same cluster (intra-cluster distance). 
• b(i) is the minimum average distance from point i to all points in the nearest neighboring cluster (inter-cluster distance).