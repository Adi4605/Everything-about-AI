- Supervised machine learning algorithm
- Predicts a continuous numerical target using two or more independent variables (features)
- With two features, Multiple Linear Regression produces a plane.
- With more than two features, it produces a hyperplane in higher-dimensional area.

Formula:
![[Pasted image 20260824162504.png]]
![[Pasted image 20260824162536.png]]

**Working:**
Dataset
   ↓
Select Features
   ↓
Split Data
   ↓
Train Model
   ↓
Learn Coefficients
   ↓
Generate Predictions
   ↓
Calculate Error
   ↓
Evaluate Model

- A common method for  finding Multiple Linear Regression is Ordinary Least Squares (OLS)
- It minimizes the sum of squared residuals
	![[Pasted image 20260824163210.png]]
- The residual is 
	![[Pasted image 20260824163230.png]]

- Multiple Linear Regression can be represented using matrices:
	![[Pasted image 20260824163315.png]]
	![[Pasted image 20260824163335.png]]
- For large datasets, coefficients can also be learned using [[Gradient Descent]].
- The algorithm tries to minimize Mean Squared Error ([[MSE]])