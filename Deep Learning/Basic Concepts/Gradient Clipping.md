- Technique used to prevent the [[Exploding Gradient Problem]] during [[Backpropagation]].
- 'Gradient Clipping restricts the maximum size of gradients during training so that weight updates remain stable.'
- Gradient is restricted before updating weights.

**Training pipeline:**
Forward Propagation
       ↓
Loss Calculation
       ↓
Backpropagation
       ↓
Compute Gradients
       ↓
Gradient Clipping
       ↓
Weight Update

Types:
1. Clip by Value : Each gradient is restricted individually.
		Formula:
		 ![[Pasted image 20260615164258.png]]
		 where:
		 g = gradient
		 c = clipping threshold

2. Clip by Norm : Instead of clipping each value separately, we look at the entire gradient vector.
		Formula:
		If  ||g|| > c
		then ![[Pasted image 20260615164602.png]]
		where:
		g = original gradient
		c = threshold

Benefits:
- Prevents Exploding Gradients
- Stabilizes training
- Faster convergence
- Better deep neural training
- Prevents numerical overflow

Drawbacks:
- Can slow learning
- Requires hyperparameter selection
- Doesn't solve [[Vanishing Gradient Problem]]
