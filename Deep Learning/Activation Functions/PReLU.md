- Parametric Rectified Linear Unit
- Improved version of ReLU and Leaky ReLU
- Helps to solve the [[Dying ReLU Problem]]
- It improves the leaky ReLU by making the negative slope learnable 

Formula of PReLU:
![[Pasted image 20260507173644.png]]

![[Pasted image 20260506172052.png|384]]

- It has better learning capability
- Faster convergence : Training can become faster in deep networks
- Often performs better than ReLU in very deep neural networks
- Each neuron may need an additional parameter *a*
- More parameters can sometimes cause overfitting 