- A numerical stability problem occurs when calculations produce incorrect or unreliable results because computers cannot represent extremely large or extremely small numbers accurately.

Five major numerical stability problems:
1. Overflow: Occurs when  a computed number becomes too large for the computer to represent
2. Underflow: Occurs when numbers become too close to zero
3. Division by Zero: Even values very close to zero can produce extremely large numbers.
4. Loss of Precision (Rounding Error): Computers cannot exactly represent many decimal numbers.
5. Catastrophic Cancellation: Occurs when subtracting two nearly equal numbers.

Techniques to improve Numerical Stability:
1. Log-Sum-Exp Trick: 
	Used in [[Softmax]] and probabilistic models
	Instead of computing very large exponentials directly, rewrite the expression to keep numbers in a safe range.

2. Add Epsilon (ε):
	Avoid division by zero or taking the logarithm of zero.

3. [[Gradient Clipping]]: Prevents [[Exploding Gradient Problem]]

4. Batch Normalization: Keeps activations within a reasonable range.

5. Methods like [[Xavier Initialization]] and [[He Initialization]] help avoid  unstable activations.

6. Stable Implementations: Use built in functions such as: [[Cross Entropy Loss]] and Binary Cross Entropy

Advantages:
- Prevent NaN values
- Prevent Infinity values
- Stable training
- Faster convergence
- Reliable predictions