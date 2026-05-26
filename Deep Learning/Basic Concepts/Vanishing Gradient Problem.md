- Occurs when : Gradients become extremely small during backpropagation
	- Which results in :
		- Weight updates become tiny
		- Early layers learn very slowly
		- Deep networks fail to train properly
- Main reason is repeated multiplication of small derivatives
- During backpropagation :
	- Gradients are propagated from output to input layer
	- In deep networks, gradients are multiplied repeatedly
	- If gradient less than 1, repeated multiplication makes them extremely small
	
- Gradient : It tell us how much weight should change
	     They are calculated using Backpropagation
	     Determines direction of learning, magnitude of weight update


Effects:
- Slow Training 
- Poor accuracy
- Deep networks fail
- Early layers stop updating