- Often performs better than [[ReLU]]
- Unlike ReLU : No sharp corner and Smooth gradients
- Non-monotonic graph
- Small negative outputs allowed
- Avoids dead neurons
- Works well in Deep Networks
- Computationally expensive
- Slower computation
- Developed by google researchers

Formula for Swish :
*f(x) = x . σ(x)*
where:
- x = input
- σ(x) = sigmoid function

Working:
Swish multiplies:
- Input *x*
	with
- Sigmoid of *x*

Derivative of Swish :
f′(x)=σ(x)+xσ(x)(1−σ(x))
- Smooth 
- Helps stable gradient flow

![[Pasted image 20260515171925.png|421]]