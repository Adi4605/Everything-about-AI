A **Confusion Matrix** is a table used to evaluate the performance of a classification model by comparing Actual Values vs Predicted Values.

![[Pasted image 20260325195219.png]]

1. True Positive (TP):
	- Model correctly predicts positive
	- Example: Sick person -> predicted as sick
2. True Negative (TN):
	- Model correctly predicts negative
	- Example: Healthy person -> predicted as Healthy
3. False Positive (FP):
	- Model predicts positive, but actually negative
	- Example: Healthy person -> Predicted as Sick
4. False Negative (FN):
	- Model predicts negative, but actually positive
	- Example: Sick person -> predicted as Healthy


Key Points:
- Confusion matrix = comparison table
- Contains: TP, TN, FP, FN
- Used to calculate: Accuracy, Precision, Recall, F1
- Helps identify model mistakes