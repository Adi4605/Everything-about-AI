 The activation function introduces non-linearity into the network, allowing it to learn and model complex relationships in the data.

Types of Activation Function:
1. [[Linear Activation Function]]: It is also known as "no activation" or "identity function", is where the activation is proportional to the input.
2. [[Sigmoid]]: Outputs values between 0 and 1. It is used in binary classification tasks like deciding if an image is a cat or not.
3. [[ReLU]](Rectified Linear Unit): A popular choice for hidden layers, it returns the input if positive and zero otherwise. It helps to solve the [[Vanishing Gradient Problem]].
4. [[Tanh]] (Hyperbolic Tangent):  Similar to sigmoid but outputs values between -1 and 1. It is used in hidden layers when a broader range of outputs is needed.
5. [[Softmax]]: Converts raw outputs into probabilities used in the final layer of a network for multi-class classification tasks.
6. [[Leaky ReLU]]: A variant of ReLU that allows small negative values for inputs helps in preventing “dead neurons” during training.
7. [[PReLU]]: Negative slope is treated as a learnable parameter, allowing better gradient flow and reducing the [[Dying ReLU Problem]].
8. [[ELU]]: Uses linear output for positive inputs and exponential function for negative inputs.
9. [[SELU]]: Scales the ELU function to create self-normalizing neural network 
10. [[Softplus]]: It is approximation of ReLU to provide smoother gradients and improved optimization in neural networks.
11. [[Softsign]]: It provides gradual saturation and smoother gradient behavior compared to Tanh.
12. [[Swish]]: Uses sigmoid function to improve gradient flow and model performance compared to ReLU.
13. [[Mish]]: It is designed to improve gradient flow, training stability and performance in deep neural networks.
14. [[GELU]]: It is used extensively in transformer-based deep learning models for improved gradient flow and performance.
15. 