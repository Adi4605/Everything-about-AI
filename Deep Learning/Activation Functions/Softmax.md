- Mainly used for multiclass classification problems, neural networks, deep learning models
- The probabilities:
	- Lie between 0 and 1
	- Sum to 1
- Mostly used in output layer
- Works well with backpropagation
- Usually used with [[Cross-Entropy Loss]]
- Often faces [[Numerical Stability Problem]]
- Sensitive to large values
- Computationally expensive
- Not suitable for multi-label classification
Formula:
![[Pasted image 20260524182729.png|166]]
where:
![[Pasted image 20260524182816.png]]

Working:
1. take exponentials of all outputs
2. Sum all exponentials
3. Divide each exponential by total sum
This normalizes outputs into probabilities

![[Pasted image 20260524183159.png|438]]