ROC = Receiver Operating Characteristic Curve

It is a **graph that shows the performance of a classification model at different threshold values.**
It plots:
- X-axis -> false Positive Rate (FPR)
- Y-axis -> True Positive Rate (TPR / Recall)

**True Positive Rate (TPR)**
TPR = $\frac{TP}{TP + FN}$
- Same as Recall
- Measures how many actual positives are detected

**False Positive Rate (FPR)**
FPR = $\frac{FP}{FP+TN}$
- Measures how many negatives are wrongly predicted as positive.

**How ROC Curve is Created?**
A classification model outputs probabilities (e.g., 0 to 1)
We choose a threshold to convert probability into class:
- If probability >= threshold -> Positive
- Else -> Negative

**Starts from (0,0)**
**Ends at (1,1)**

High TPR (close to 1)
Low FPR (close to 0)
- Ideal Point -> (0,1)

**AUC = Area under the Curve**
- It measures how well the model can distinguish between classes

**"Probability that the model ranks a random positive sample higher than a random negative sample."**


Key Points:
- ROC curve plots TPR vs FPR
- AUC = Area under ROC curve
- Higher AUC -> better model
- Diagonal line -> random model 
- Ideal Point -> (0,1)