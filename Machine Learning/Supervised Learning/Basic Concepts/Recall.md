**"Out of all actual positive cases, how many did the model correctly identify?"**

Recall = $\frac{TP}{TP+FN}$
where, 
- TP(True Positive) -> Correct positive predictions
- FN(False Negative) -> Missed positive cases

Recall answers:
- High Recall -> Detects most positives
- Low Recall -> Misses many positives

Recall in Multi-class Classification
- Calculated for each class separately
- Then averaged:
	- Macro recall
	- Micro recall
	- Weighted recall


Related terms:
- Sensitivity = Recall
- True Positive Rate (TPR) = Recall


Key Points:
- Measures ability to detect positives
- Important when FN is costly
- Also called Sensitivity