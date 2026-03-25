**"Out of all actual negative cases, how many did the model correctly identify?"**

Specificity = $\frac{TN}{TN+FP}$
where,
TN (True Negative) -> Correct negative predictions
FP (False Positive) -> Incorrect positive predictions

High Specificity -> Few false alarms
Low Specificity -> Many false alarms

Trade-off Between Sensitivity and Specificity
- Increasing sensitivity -> may reduce specificity
- Increasing specificity -> may reduce sensitivity
- Controlled by decision threshold

Relationship with False Positive Rate
***FPR = 1 - Specificity***
- If Specificity is high -> FPR is low


Key Points:
- Measures correct identification of negatives
- Opposite of false positive rate
- Important when false positives matter