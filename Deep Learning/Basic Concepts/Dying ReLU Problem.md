- It occurs when a neuron always outputs 0 and stops learning permanently, such neurons are called 'Dead Neurons'.
- Gradient becomes 0
- Weights stop updating

How neuron dies:
1. Weights become unfavorable
2. Neuron outputs negative values frequently
3. ReLU converts outputs to 0
4. Gradients become 0
5. Weights stop updating
6. Neuron permanently outputs 0

Causes:
- Large negative weights
- High learning rate
- Poor weight initialization
- Deep networks

Effects:
- Reduced learning capacity
- Lower accuracy
- Sparse network
- Training instability