- Improved version of ELU and ReLU
- Enables self-normalizing neural networks
- Faster and more stable training
- Better performance in deep networks
- More computational cost
- Requires specific conditions like normalized inputs, proper weights initialization, [[AlphaDropout]] is used instead of normal dropout.
- Not always better than ReLU
- Helps prevent vanishing/ exploding gradients

**Self-Normalizing** : 
	In deep neural networks, activations can become:
	- Too large -> exploding activations
	- Too small -> vanishing activations
	SELU automatically keeps:
	- Mean close to 0
	- Variance close to 1
	This helps stabilize training

Formula of SELU:
![[Pasted image 20260507174646.png]]

![[Pasted image 20260507174815.png|442]]