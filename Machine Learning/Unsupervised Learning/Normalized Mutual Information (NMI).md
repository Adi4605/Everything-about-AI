Evaluates clustering, that measures the similarity between two clusterings (like predicted clusters vs. true labels) by scaling the mutual information (shared information) between them.

Range of 0 (no shared info) to 1 (perfect match)

Uses the entropies of the labels as normalization factors, and is useful because it's independent of label permutation

Working:
- **Mutual Information (MI):** First, it calculates how much information two label sets (e.g., true classes 𝑌 and predicted clusters 𝐶) share, using their joint and marginal probabilities.
- **Entropy:** It then finds the entropy (uncertainty/information content) for both the true labels H(Y) and the predicted labels H(C).
- **Normalization:** The MI is divided by a normalization factor, often the average (arithmetic, geometric, or max) of the two entropies, to scale the result between 0 and 1.
-  **Result:** A value closer to 1 means the clusterings align well with each other; a value near 0 means little shared information.

Formula: ![[Pasted image 20260101114856.png]]
where, 
• U and V are two clustering assignments. 
• I(U,V) is the mutual information between U and V, measuring the amount of shared information. • H(U) and H(V) are the entropies of U and V, representing the uncertainty in each clustering assignment.

NMI ranges from 0 to 1: 
• 1: indicates a perfect match between the two clusterings.
• 0: suggests that the clusterings are independent.
