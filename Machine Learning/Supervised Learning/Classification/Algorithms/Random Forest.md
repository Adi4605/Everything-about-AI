- Random forest is used for both classification and regression.
- Combines multiple decision trees to make better predictions.
- 'Random forest is an ensemble learning algorithm that builds multiple decision trees and combines their outputs to improve accuracy and reduce overfitting.'
- Each tree is trained on random data samples and random features.

Working:
1. Bootstrap Sampling: Random forest multiple datasets from the original dataset using [[Bagging]] (Bootstrap Aggregation)
2. Build decision trees: each tree is trained independently
3. Random feature selection: Random forest selects only a random subset
4. Final prediction: Classification uses majority voting and Regression uses average prediction

Architecture:
![[Pasted image 20260601125231.png]]

Hyperparameters of Random Forest
1. n_estimators: Number of trees
2. max_depth: Maximum depth of trees
3. min_samples_split: Minimum samples required to split a node
4. min_samples_leaf: Minimum samples in a leaf node
5. max_features: Number of random features considered at each split

Advantages:
- High accuracy
- Reduces overfitting
- Handles large datasets
- Handles missing values
- Can identify important features
- Works for classification and regression

Disadvantages:
- Slower than decision trees
- Higher memory usage
- Less interpretable


- Out-of-Bag (OOB) Error: Some data samples are not selected during bootstrap sampling.