The activation function introduces non-linearity into the network, allowing it to learn and model complex relationships in the data.

Types of Activation Function:
1. [[Sigmoid Function]]: Outputs values between 0 and 1. It is used in binary classification tasks like deciding if an image is a cat or not.
2. [[ReLU]](Rectified Linear Unit): A popular choice for hidden layers, it returns the input if positive and zero otherwise. It helps to solve the [[Vanishing Gradient Problem]].
3. [[Tanh]] (Hyperbolic Tangent):  Similar to sigmoid but outputs values between -1 and 1. It is used in hidden layers when a broader range of outputs is needed.
4. [[Softmax]]: Converts raw outputs into probabilities used in the final layer of a network for multi-class classification tasks.
5. [[Leaky ReLU]]: A variant of ReLU that allows small negative values for inputs helps in preventing “dead neurons” during training.