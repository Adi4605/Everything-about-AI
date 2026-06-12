- [[Regularization]] technique used in neural network to reduce [[Overfitting]].
- During training, randomly "drop" (deactivate) some neurons so the network cannot rely too heavily on any single neuron.
- Dropout rate represents the fraction of neurons removed.

Working:
1. Input enters the network.
2. Random neurons are selected.
3. Selected neurons are dropped. Output becomes zero.
4. Remaining neurons continue processing.
5. [[Backpropagation]] updates only active neurons.
6. Next iteration generates a completely new dropout mask.

Inverted Dropout:
Instead of scaling during testing, activations are scaled during training.

Types:
1. Standard Dropout: Random neurons removed.
2. Spatial Dropout: Drops entire feature maps rather than individual neurons. Used in CNNs.
3. Gaussian Dropout: Applies multiplicative Gaussian noise.
4. Alpha Dropout: Designed for SELU activation functions. Maintains mean and variance.
5. Variational Dropout: Used in recurrent networks and Bayesian neural networks.