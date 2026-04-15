**Binary Classification** is a type of supervised learning where the model predicts one of two possible classes.

In Binary Classification:
- Input -> X (features)
- Output -> Y ∈ {0,1}
where,
0 = Negative Class
1= Positive Class

Working:
1. Collect labeled data
2. Train model on features + labels
3. Model learns decision boundary
4. Predict probability for new data
5. Convert probability -> class using threshold


Changing threshold affects:
- High threshold = High precision, low recall
- Low threshold = High recall, low precision


Binary Classification uses:
- Log Loss (Binary Cross-Entropy)
	- Loss = -[ylog(p) + (1-y)log(1-p)]


Key Points:
- Binary Classification -> 2 classes
- Output ∈ {0,1}
- Uses [[Confusion Matrix]]
- Metrics: Accuracy, Precision, Recall , F1
- Threshold plays key role