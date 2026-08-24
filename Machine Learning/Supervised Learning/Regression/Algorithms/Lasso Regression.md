- Lasso -> Least Absolute Shrinkage and Selection Operator
- Regularized version of Linear Regression that uses L1 regularization to reduce overfitting and control large model coefficients and performs automatic feature selection
- Linear regression with an L1 penalty **shrinks coefficients toward zero and can make some coefficients exactly zero**.
- It produces a [[Sparse Model]]

Formula: 
	![[Pasted image 20260824173938.png]]
	![[Pasted image 20260824173953.png]]

- L1 regularization -> Adds the absolute value of the weights as a penalty. It can drive some weight values to zero, which performs automatic feature selection.
	![[Pasted image 20260824174125.png]]
	- λ is a hyperparameter which controls how strongly Lasso penalizes large coefficients.
Working:
Training Data
      ↓
Calculate Predictions
      ↓
Calculate Prediction Error
      ↓
Calculate L1 Penalty
      ↓
Error + Penalty
      ↓
Optimize Coefficients
      ↓
Some Coefficients Become Zero

- Lasso is optimized using algorithms like:
	1. [[Coordinate Descent]]
	2. [[LARS]] (Least Angle Regression)
	3. [[Proximal Gradient Methods]]

Simplified:
                  LASSO REGRESSION
                         ↓
                 Linear Regression
                         ↓
                  Add L1 Penalty
                         ↓
                 λ × Σ|Coefficient|
                         ↓
	              Shrink Coefficients
                         ↓
	          Some Coefficients Become 0
                         ↓
	               Feature Selection
                         ↓
                Reduced Model Complexity
                         ↓
	               Less Overfitting