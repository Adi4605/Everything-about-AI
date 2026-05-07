Exponential Linear Unit
It introduces an exponential curve for negative values instead of making them completely zero.

- Improves ReLU and Leaky ReLU
- Reduces the [[Dying ReLU Problem]]
- Improves learning speed
- Make training more stable
- Allows non-zero gradients
- Faster convergence
- Mean Activation Closer to Zero: Negative outputs help center data around zero
- More computationally expensive
- Slower than ReLU

Formula of ELU:
![[Pasted image 20260507173526.png]]

![[Pasted image 20260507173745.png]]
