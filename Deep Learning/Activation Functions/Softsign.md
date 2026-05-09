- Compresses input values into the range -1 to 1
- Simpler than [[Tanh]]
- Slower saturation
- Gradients decrease more gradually
- [[Vanishing Gradient Problem]]
- Uses simple division instead of exponentials

Formula: 
![[Pasted image 20260509135856.png]]
where:
- x = input
- |x| = absolute value of x

Case 1: Large Positive Input
	If x -> +∞
	then f(x) -> 1
Case 2: Large Negative Input
	If x -> -∞
	then f(x) -> -1
Case 3: Input Near Zero
	If  x = 0
	then f(0) = 0


![[Pasted image 20260509140532.png|458]]
