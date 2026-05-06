- Parametric Rectified Linear Unit
- Improved version of ReLU and Leaky ReLU
- Helps to solve the [[Dying ReLU Problem]]
- It improves the leaky ReLU by making the negative slope learnable 

Case 1: Positive Input
	If x>0 
	then  f(x) = x
	The value passes unchanged.
	
Case 2: Negative Input
	If x<=0
	then f(x) = ax    # '*a*' is learned automatically during the training
	Instead of becoming 0 completely, a small negative value is allowed.

![[Pasted image 20260506172052.png|384]]

- It has better learning capability
- Faster convergence : Training can become faster in deep networks
- Often performs better than ReLU in very deep neural networks
- Each neuron may need an additional parameter *a*
- More parameters can sometimes cause overfitting 