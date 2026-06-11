- Used for Classification, Regression, Outlier detection
- Performs well on small-medium sized datasets, High-dimensional Data, Text Classification, Image Classification
- 'Supervised learning algorithm that finds the optimal hyperplane that best separates data points belonging to different classes while maximizing the margin between them.'
- Hyperplane - It is aa decision boundary that divides data into classes.
- SVM chooses the hyperplane with the maximum margin
- Margin - Distance between Hyperplane and Nearest data points
- SVM is also called as 'Maximum Margin Classifier'
- SVM uses '[[Kernel Functions]]'
- Uses [[Regularization Parameter (C)]] hyperparameter and [[Gamma Parameter]]
- SVM for regression is call '[[Support Vector Regression]]'

Working:
1. Input training data
2. Find possible hyperplanes
3. Calculate margins
4. Select hyperplane with maximum margin
5. Use it for prediction

Mathematical Representation:
Suppose,
x=(x1​,x2​,…,xn​)

![[Pasted image 20260611153925.png]]

Classification rule: 
If  Hyperplane > 0:
	Class = Positive
If  Hyperplane < 0:
	Class = Negative

Types of SVM:
1. Linear SVM: Used when  data is linearly separable
			A straight line can separate classes
2. Non-linear SVM: Many real datasets are not linearly separable.
			A straight line cannot separate classes
3. Hard Margin SVM: Used when no misclassification allowed
			Condition: Data is perfectly separable
4. Soft Margin SVM: Allows some misclassification. Used in real world datasets

Advantages:
- High  accuracy
- Effective in High dimensions
- Handles non linear data
- Robust against overfitting
- Works with small datasets

Disadvantages:
- Slow on large datasets
- Difficult to interpret
- Choosing kernel is difficult
- Sensitive to Parameter Tuning