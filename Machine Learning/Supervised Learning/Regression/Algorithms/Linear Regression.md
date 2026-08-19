- Supervised learning algorithm
- Used to predict continuous numerical value by finding a linear relationship between input features and the target variables.
- Finds the best-fit straight line through the data so that it can predict the value of a continuous target
- It assumes a linear relationship between the features and the target
Formula:
![[Pasted image 20260819112525.png]]
![[Pasted image 20260819112538.png]]
![[Pasted image 20260819112908.png]]
- Slope b1 tells how much the predicted target changes when x increase by one unit
- Residual : Difference between the actual value and predicted value
 ![[Pasted image 20260819113054.png]]
 - Standard Linear Regression algorithm uses **Ordinary Least Squares (OLS)** method and tries to minimize the sum of squared residuals
 - The objective is
  ![[Pasted image 20260819113312.png]]

Working:
Training Data
     ↓
Calculate Relationship
     ↓
Find Best-Fit Line
     ↓
Minimize Prediction Error
     ↓
Learn Coefficients
     ↓
Use Coefficients for Prediction

Evaluation Metrics Used are:
1. [[MAE]]
2. [[MSE]]
3. [[RMSE]]
4. [[R2 Score]]

