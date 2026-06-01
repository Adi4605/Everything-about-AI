- Used for both classification and regression
- Predicts the output of a new data point by looking at the K-nearest data points in the training dataset
- 'KNN is a supervised learning algorithm that classifies or predicts a data point based on the majority class (for classification) or average value (for regression) of it's K nearest neighbors' 

Working:
1. Choose K: Select the value of K
2. Calculate Distance: Computer distance between the new data point and all training points.
![[Pasted image 20260601132930.png]]
3. Sort Distances: Arrange distances from smallest to largest
4. Select K nearest Neighbors: Choose closest points
5. Make prediction: For classification - Use majority voting 
		        For regression - Take average value

Meaning:
- K - Number of nearest neighbors considered
- Nearest - Closest data points based on distance
- Neighbors: Nearby training examples

Distance metrics in KNN:
1. Euclidean Distance:
![[Pasted image 20260601133522.png]]
2. Manhattan Distance:  
![[Pasted image 20260601133617.png]]
3. Minkowski Distance: Generalized distance metric
4. Hamming Distance: Used for categorical data

Advantages: 
- Easy of understand
- No training phase
- Works for classification and regression
- Effective for small datasets
- No assumptions about data distribution

Disadvantages:
- Slow for large datasets
- Memory intensive
- Sensitive to noise
- Sensitive to feature scaling

Hyperparameters:
1. n_neighbors: Number of neighbors
2. metric: Distance metric
3. weights: How neighbors contribute