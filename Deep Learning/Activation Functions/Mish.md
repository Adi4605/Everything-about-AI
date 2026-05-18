- Improvement over [[ReLU]] and [[Swish]]
- Non-monotonic
- Self-Regularized
- Small negative outputs allowed
- Smooth transition near zero
- Provides better accuracy
- Avoids dead neurons
- Computationally expensive
- More complex
- Higher memory usage

Formula:
![[Pasted image 20260518184526.png]]
This can also be written as:
f(x)=x⋅tanh(softplus(x))

Components of Mish:
Mish combines:
- Input x
- Softplus function
- Tanh Activation
Step-by-step:
- Compute softplus
- Apply tanh
- Multiply by input

![[Pasted image 20260518184456.png|524]]