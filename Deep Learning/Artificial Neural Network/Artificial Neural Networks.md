 Systems designed to mimic how the human brain processes information.
 ANNs use artificial neurons to analyze data, identify patterns and make predictions.
 These networks consist of layers of interconnected neurons that work together to solve complex problems.
 ![[Pasted image 20260102134620.png]]

Components of ANN
- **Input Layer** :  Data such as an image, text or number is fed into the network through the input layer.
- **Hidden Layers** : Each neuron in the hidden layers performs some calculation on the input, passing the result to the next layer. The data is transformed and abstracted at each layer.
- **Output Layer** : After passing through all the layers, the network gives its final prediction like classifying an image as a cat or a dog.
The process of [[Backpropagation]] is used to adjust the weights between [[Neurons]].

Types of Artificial Neural Networks : 
1. [[Feedforward Neural Network (FNN)]]
2. [[Convolutional Neural Network (CNN)]]
3. [[Radial Basis Function Network (RBFN)]]
4. [[Recurrent Neural Network (RNN)]]

Optimization Algorithms:
1. [[Gradient Descent]] : Most basic optimization algorithm that updates weights by calculating the gradient of the loss function.
2. [[Adam (Adaptive Moment Estimation)]] : An efficient version of gradient descent that adapts learning rates for each weight used in deep learning.
3. [[RMSprop]] : A variation of gradient descent that adjusts the learning rate based on the average of recent gradients, it is useful in training recurrent neural networks (RNNs).
4. [[Stochastic Gradient Descent (SGD)]] : Updates weights using one sample at a time helps in making it faster but more noisy.