- Occurs when: Gradients become extremely large during backpropagation.
- Which results in:
	- Weight updates become huge
	- The model becomes unstable
	- Loss may oscillate wildly or become infinite
	- Training can completely fail
- Main reason if derivatives are greater than 1, the gradient can grow exponentially.

Causes:
- Deep networks: Many layers mean many derivative multiplications
- Large weight initialization
- High learning rate
- Recurrent neural networks

Solution:
1. [[Gradient Clipping]]
2. Proper Weight Initialization
3. Lower Learning Rate
4. Batch Normalization
5. Better Architectures

