The model predicts one class out of more than two possible classes.

In Multi-class Classification:
- Input -> X (features)
- Output -> Y ∈ {1,2,3,4,....,K}
where,
K = number of classes
Each sample belongs to exactly one class

Working:
1. Collect labeled data
2. Train model with multiple class labels
3. Model learns patterns for each class
4. Outputs probabilities for all classes
5. Choose class with highest probability

Loss Function:
- Categorical Cross-Entropy:
	- Loss = -∑$y_i$​log($p_i$​)


Challenges:
- Class Imbalance: Some classes have fewer samples
- Overlapping classes: Hard to separate
- High Dimensionality: Complex feature space
- Computational Complexity: More classes -> more complexity

Techniques to handle challenges:
- Data balancing
- Feature engineering
- Regularization
- Ensemble methods


Key points:
- Multi-class -> more than 2 classes
- Uses [[Softmax]] function
- Evaluation uses macro/micro averaging
- Confusion Matrix is larger
- Algorithms: Trees, SVM (OvR), NN