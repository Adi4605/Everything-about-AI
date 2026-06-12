- Explains why the model underfit or overfit and how to find the right balance between them.

Bias : Error caused by making overly simple assumptions about the data.
- A high-bias model cannot learn the true relationship between inputs and outputs.
- Causes of High Bias:
	- Model is too simple
	- Misses important patterns
	- High training error
	- High testing error
	- Causes [[Underfitting]]

Variance : Error caused by a model being too sensitive to training data.
- A high-variance model learns not only the actual pattern but also the noise.
- Characteristics of High Variance:
	- Model is too complex
	- Learns noise
	- Very low training error
	- High testing error
	- Causes [[Overfitting]]

Scenarios:
Scenario 1: High Bias + Low Variance (Underfitting)
- Doesn't learn patterns
- Poor performance everywhere

Scenario 2: Low Bias + High Variance (Overfitting)
- Memorizes training data 
- Fails on new data

Scenario 3:  Low Bias + Low Variance (Good Fit)
- Learns patterns
- Generalizes well

Scenario 4: High Bias + High Variance (Worst Fit)
- Training performance is poor
- Testing performance is poor
- Predictions are inconsistent


![[Pasted image 20260612170210.png]]
