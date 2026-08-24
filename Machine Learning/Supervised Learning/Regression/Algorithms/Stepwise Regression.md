- Feature selection technique
- used with regression models to automatically select a useful subset of predictor variables.
- Adds or removes features step-by-step based on a statistical criterion.
- Automatic variable-selection method that repeatedly adds or removes predictors to find a simpler regression model containing the most useful variables.

**Working:**
	            Dataset
                   ↓
             Data Preprocessing
                   ↓
             Train/Test Split
                   ↓
          Start Feature Selection
                   ↓
        ┌───────────┴───────────┐
	    ↓                                          ↓
     Add Feature           Remove Feature
             ↓              ↓
           Evaluate Model
                ↓
          Continue Selection
                ↓
             Final Features
                ↓
            Train Final Model
                ↓
             Test Model

Types:
1. Forward Selection :
	- Start with no predictors and add useful predictors one at a time
		No Features
		    ↓
		Try Every Feature
		    ↓
		Choose Best Feature
		    ↓
		Add Next Best Feature
		    ↓
		 Repeat
		    ↓
		Final Model

2. Backward Elimination :
	- Start with all features and remove the least useful feature step-by-step
	  All Features
	     ↓
	  Fit Model
	     ↓
	Find Least Useful Feature
	     ↓
	  Remove It
	     ↓
	  Fit Again
	     ↓
	   Repeat
	     ↓
	  Final Model

3. Bidirectional Stepwise Selection :
	- Combines Forward Selection + Backward Elimination
	- At each step, the algorithm can:
		Add a useful feature
		 OR 
		Remove an unnecessary feature

How does Stepwise Regression Decide which Feature to Add or Remove:
1. p-value
2. R²
3. Adjusted R²
4. AIC (Akaike Information Criterion)
5. BIC (Bayesian Information Criterion)
6. Cross-validation error


Simplified:
         STEPWISE REGRESSION
                   ↓
            Feature Selection
                   ↓
       ┌─────────────┼─────────────┐
       ↓                        ↓                        ↓
   Forward             Backward         Bidirectional
   Selection          Elimination          Selection
       ↓                        ↓                       ↓
      Add              Remove        Add + Remove
                   ↓
              Selection Criterion
                   ↓
        p-value / AIC / BIC / CV
                   ↓
             Final Feature Set

Stepwise Regression is not another type of regularization like [[Ridge Regression]] or [[Lasso Regression]]. It is a feature-selection strategy that builds a regression model by sequentially adding and/or removing predictors according to a chosen criterion.