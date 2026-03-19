Measures the similarity between two data partitions (like predicted clusters vs. true labels) while correcting for agreements that happen by random chance.

Gives scores from -1 (perfect disagreement), +1 (perfect match), 0 (random agreement).

Working
- **Compares Pairs**: ARI looks at all possible pairs of data points and counts how many are grouped together or apart in both clustering.
- **Corrects for Chance**: It normalizes the basic Rand Index by subtracting the expected similarity from random clustering, preventing inflated scores for random groupings.
- **Uses a Contingency Table**: A table summarizing the overlap between the two partitions is used for calculation.

Formula: ![[Pasted image 20260101113311.png]]
where:,
• RI (Rand Index) counts the agreement between pairs of elements, considering pairs that are either in the same cluster in both clustering or in different clusters in both.
• E[RI] represents the expected RI under a random model.

The ARI ranges from -1 to 1: 
	• 1: indicates perfect clustering agreement with ground truth. 
	• 0: reflects random labeling. 
	• Negative values indicate worse-than-random labeling.
	
- **Symmetry**: `adjusted_rand_score(A, B)` is the same as `adjusted_rand_score(B, A)`.