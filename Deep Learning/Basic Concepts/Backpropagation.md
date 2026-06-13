- Backward propagation of errors.
- It is the algorithm used to train neural networks by updating their weights and biases to minimize error.
- 'Backpropagation is a process that calculates how much each weight contributed to the error and adjusts the weights to reduce that error.'

**Working:**

Prediction
    ↓
Calculate Error
    ↓
Find Cause
    ↓
Update Weights
    ↓
Improve Prediction

Step-by-step Backpropagation:
1. Forward pass: Calculate prediction.
2. Calculate Loss: Determine prediction error
3. Compute Output Layer Gradient: Find how output weights affect loss.
4. Move backward: Calculate hidden layer gradients.
5. Update weights: Reduce error.
6. Repeat: Continue for many epochs.

Advantages:
- Efficient
- Automatic Learning
- Scalable
- Accurate

Disadvantages:
- [[Vanishing Gradient Problem]]
- [[Exploding Gradient Problem]]
- Requires Differentiable Functions
- Computationally expensive

Overall Training Process:
Steps:
1. [[Forward Propagation]]: Calculate prediction.
2. [[Loss Function]]: Calculate error.
3. Backpropagation: Compute gradients.
4. [[Gradient Descent]]: Update weights.
5. Repeat until convergence.