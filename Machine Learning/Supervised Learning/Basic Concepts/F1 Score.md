**F1 Score** is the harmonic mean of Precision and Recall.

F1 = 2.$\frac{Precision . Recall}{Precision + Recall}$

F1 = $\frac{2TP}{2TP + FP + FN}$

Why do we need F1 score?
	Sometimes:
	- Precision is high, but recall is low
	- Recall is high, but precision is low
	- Accuracy alone cannot capture this balance


High F1 -> Good precision + Good recall
Low F1 -> Poor performance in one or both


F1 uses Harmonic Mean, not average:
Because:
- It penalizes extreme values
- If one value is very low -> F1 becomes low

F1 score value = 1 -> Perfect Model
F1 Score value = 0 -> Worst Model

**F1 Score in Multi-class Classification:**
Calculated using:
1. Macro F1
	- Average of F1 scores of all classes
	- Treats all classes equally
2. Micro F1
	- Based on total TP, FP, FN
	- Useful for imbalanced data
3. Weighted F1
	- Weighted by class frequency


Key Points:
- F1 = Harmonic mean of precision and recall
- Used when both metrics are important
- Good for imbalanced data
- Range: 0 to 1