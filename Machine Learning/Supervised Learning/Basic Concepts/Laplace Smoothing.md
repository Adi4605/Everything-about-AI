- Technique used in [[Naïve Bayes]] and other probabilistic models to solve the [[Zero Probability Problem]]
- It ensures that every possible feature gets at least a small probability, even if it never appeared in the training data.
- Adds 1 to every count before calculating probabilities, it means to pretend every category has seen once.

Formula with smoothing:
![[Pasted image 20260603160545.png]]

Advantages:  
- Eliminates zero probabilities
- Improves generalization
- Essential for Naïve Bayes
- Simple to implement

Disadvantages:
- Introduces Bias
- Can overestimate rare events
- Less effective for very large vocabularies