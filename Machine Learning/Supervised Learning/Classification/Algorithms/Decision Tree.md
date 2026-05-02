- Used for classification and regression
- Works like a flowchart
	- Each internal node -> a question (feature test)
	- Each branch -> answer to that question
	- Each leaf node -> final prediction
- Splits data based on features to make predictions
- Decision trees overfit very easily
- Uses [[Pruning]] to solve overfitting
- 
![[Pasted image 20260502111724.png]]

Working:
1. Start with full dataset
2. Choose the best feature to split data
3. Divide data into subsets
4. Repeat recursively for each subset
5. Stop when:
	- Data is pure OR
	- Maximum depth reached

How to choose the best split:
1. Entropy (Measure of impurity):
![[Pasted image 20260502112301.png]]

2. Information Gain:
	*IG = H(parent) - H(children)*
- Choose feature with highest information gain

2. Gini Index:
![[Pasted image 20260502112534.png]]


Types:
1. Classification Tree: Categorical Output
2. Regression Tree: Output as continuous value

