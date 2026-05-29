- Technique used to reduce te size and complexity of a of a neural network by removing unnecessary neurons, connections or weights.
- 'If some weights or neurons contribute very little to the final prediction, remove them'.

Types:
1. Weight Pruning: Removes individual weights with very small magnitudes.
2. Neuron Pruning: Removes entire neurons that contribute little.
3. Structured Pruning: Removes complete structures:
					- Filters
					- Channels
					- Neurons
					- Layers
4. Unstructured Pruning: Removes individual weights only.

- Based on Timing
1. Pre-Training Pruning: Pruning before training
2. During Training: Pruning while training
3. Post-Training Pruning: Pruning after training

- Magnitude based Pruning:
	- Small weight -> Remove
	- Large weight -> Keep

Pruning Process:
1. Train the network fully.
2. Measure importance of weights
3. Remove least important weights
4. Fine-tune the network
5. Deploy compressed model

Advantages:
- Smaller models
- Faster inference
- Lower memory usage
- Reduced power consumption
- Can reduce overfitting

Disadvantages:
- Accuracy loss
- Requires [[Fine-Tuning]]
- Additional complexity