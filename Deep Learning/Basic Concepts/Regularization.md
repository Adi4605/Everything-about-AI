- It is a technique used to reduce [[Overfitting]] by preventing a model from becoming too complex.
- It does this by adding a penalty term to the loss function so that the model prefers smaller and simpler weights.
- 'Regularization is a method that discourages large weights and overly complex models, helping the model generalize better to unseen data.'
- Without Regularization:
	- The model memorize training data
	- Weights can become very large
	- Training accuracy becomes very high
	- Test accuracy becomes poor
- [[Regularization Parameter (C)]] is used.
- Regularization affects the [[Bias-Variance Tradeoff]]

Types:
1. L1 Regularization (Lasso):
	- L1 adds the sum of the absolute values of weights to the loss function.
			![[Pasted image 20260615165758.png]]
	- L1 pushes weights to exactly zero.
	- Some features are completely removed.
	- Automatically performs feature selection.

2. L2 Regularization (Ridge):
	- L2 adds the sum of squared weights.
		![[Pasted image 20260615170052.png]]
	- L2 reduces large weights but usually does not make them exactly zero.
	- All features remain, but weights become smaller.

3. Elastic Net Regularization:
	- Elastic net combines L1 and L2.
		![[Pasted image 20260615170319.png]]
	- Provides feature selection from L1 and stability from L2

4. [[Dropout]]
5. [[Early Stopping]]
6. [[Data Augmentation]]
7. [[Pruning]]

Advantages:
- Reduces overfitting
- Improves generalization
- More stable models
- Prevents large weights
- Feature selection (L1)

Disadvantages:
- Can cause [[Underfitting]]
- [[Hyperparameter Tuning]] required
- Increased training complexity