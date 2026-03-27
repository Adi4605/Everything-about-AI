Each input can belong to multiple classes at the same time

In Multi-label Classification:
- Input -> X (features)
- Output -> Y = ($y_1$, $y_2$, ....., $y_k$)
where, $y_i$ ∈ {0,1}
- 1 = Label present
- 0 = Label Absent

Working:
1. Collect labeled data with multiple labels
2. Train model to predict multiple outputs
3. Model outputs probability for each label
4. Apply threshold to each label
5. Assign multiple labels

Approaches:
1. Binary Relevance
	- Treat each label as separate binary classification
2. Classifier Chains
	- Labels are predicted sequentially
	- Each prediction depends on previous labels
3. Label Powerset
	- Treat each combination of labels as a single class


Loss Function
- Binary Cross-Entropy (per label)
	Loss = -∑[ylog(p) + (1-y)log(1-p)]


Challenges:
- Label Correlation: Labels may depend on each other
- Imbalanced Labels: Some labels appear rarely
- High Dimensional Output: Many labels -> complexity increases
- Evaluation Difficulty: Multiple metrics needed


Key Points:
- Multi-label -> multiple outputs per input
- Uses sigmoid (not softmax)
- Uses binary cross-entropy
- Metrics: Hamming loss, F1, Jaccard
- Methods: Binary relevance, classifier chains

