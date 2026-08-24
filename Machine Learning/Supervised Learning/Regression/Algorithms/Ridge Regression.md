- Regularized version of Linear Regression that uses L2 regularization to reduce overfitting and control large model coefficients.
- Linear regression with an L2 penalty added to the loss function, which discourages large coefficients and improves model stability.

It is especially useful when:
- There are many features
- Features are highly correlated
- Ordinary Linear Regression is overfitting
- You want to reduce the impact of large coefficients

Formula:
![[Pasted image 20260824171313.png]]
![[Pasted image 20260824171327.png]]

- **L2 Regularization** -> Adds the squared value of the weights as a penalty. It **shrinks weights close to zero but does not set them to exact zero.**
	![[Pasted image 20260824171433.png]]
	- λ is a hyperparameter which controls how strongly Ridge penalizes large coefficients.

**Working:**
Start with training data
		 ↓
   Calculate predictions
		 ↓
Calculate prediction error
		 ↓
   Calculate L2 penalty
		 ↓
	Combine them
Total Objective=Prediction Error + Regularization Penalty
		 ↓
Find coefficients that minimize the objective

- Ridge regression can be done using [[Gradient Descent]]
- For standardized features and appropriate matrix formulation, Ridge has a closed-form solutions:
	![[Pasted image 20260824172417.png]]
	![[Pasted image 20260824172430.png]]

Simplified:
RIDGE REGRESSION
      ↓
   Linear Regression
      ↓
  Add L2 Penalty
      ↓
λ × Σ(coefficient²)
      ↓
Shrink Large Weights
      ↓
Reduce Overfitting & Multicollinearity
      ↓
Better Generalization