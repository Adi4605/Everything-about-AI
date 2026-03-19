It transforms the data into a set of linearly uncorrelated variables called principal components.

These components are ordered by the amount of variance they explain, with the first few components capturing the majority of the data's variance.

PCA works by identifying the directions (principal components) in which the data varies the most

Working Of PCA:
1. **Standardizing the Data:** Since PCA is sensitive to the scale of the data, it starts by standardizing the dataset to have zero mean and unit variance. 
2.  [[Covariance Matrix]] : The covariance matrix of the data is computed to identify relationships between different features. 
3. **[[Eigenvectors and Eigenvalues]]** : PCA then calculates the eigenvectors (directions of maximum variance) and eigenvalues (the magnitude of variance along those directions). 
4. **Selecting Principal Components:** The eigenvectors are ranked according to the eigenvalues, and the top eigenvectors (principal components) are chosen. These components are then used to reduce the dimensionality of the original dataset.

Implementation of PCA:
- Load the dataset 
- Standardizing the Data 
- Applying PCA 
- Visualizing the Principal Components 
- Plot the explained variance ratio 
- Cumulative explained variance plot 
- Projecting the Data onto the Principal Components