- Mathematical function that measures how wrong a model's prediction is compared to the actual value.
- 'A loss function tells the model how much error it has made.'
- Smaller loss means better predictions
- Without loss function:
	- Model cannot measure error.
	- Backpropagation cannot compute gradients.
	- Learning cannot occur.
- Characteristics of Good Loss Function:
	- Be differentiable
	- Penalize error
	- Guide optimization
	- Be computationally efficient

Types:
1. Regression Loss Function: Used for numerical predictions.
	- MSE
	- RMSE
	- MAE
	- Huber Loss: Combination of MAE and MSE
2. Classification Loss Function: Used for category predictions.
	- Binary Cross Entropy: Used for binary classification
	- Categorical Cross Entropy: Used for multi-class classification
	- Hinge Loss: Used in Support Vector Machine (SVM)
	- Intuition Cross Entropy
	- Sparse Categorical Cross Entropy: Same purpose as categorical cross entropy but memory efficient.