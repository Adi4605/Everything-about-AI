- Improved version of R² score 
- Takes into account the number of predictors/features used in the regression model.
- Adjusted R² increases only when the new feature provides enough useful information to justify the added complexity.
- Measures how well a regression model explains the variation in the target while penalizing the model for using unnecessary predictors.

Formula:
	![[Pasted image 20260825115848.png]]
	![[Pasted image 20260825115859.png]]

- Adjusted R² can decrease when a feature is added.