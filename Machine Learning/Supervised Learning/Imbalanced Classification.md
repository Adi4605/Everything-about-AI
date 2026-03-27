The number of samples in different classes is not equal.

Key Terminology:
- Majority Class -> Class with more samples
- Minority Class -> Class with fewer samples
- Class Imbalance Ratio -> Degree of imbalance

Techniques to handle Imbalanced data:
1. Data Level Techniques
	- Undersampling : Reduce majority class
	- Oversampling : Increase minority class
	- SMOTE : Synthetic Minority Over-Sampling Technique, Creates artificial data
2. Algorithm-Level Techniques:
	- Class Weights : Assign higher weight to minority class
	- Cost-Sensitive Learning : Penalize misclassification of minority class
	- Ensemble Methods : Random Forest, Boosting(e.g., AdaBoost, XGBoost)
3. Hybrid Techniques
	- Combine Sampling + Algorithms

Challenges:
- Biased models
- Poor minority detection
- Misleading accuracy
- Hard Evaluation


Key Points:
- Imbalanced Classification = unequal class distribution
- Accuracy is misleading
- Focus on recall, precision, F1
- Use SMOTE, oversampling, undersampling
- Handle using class weights