- Regularized version of Linear Regression that **combines L1 regularization from Lasso and L2 regularization from Ridge**.
- Combines Ridge and Lasso regularization to reduce overfitting, control large coefficients and perform feature selection.

It is especially useful when:
- You have many features
- Many features may be irrelevant 
- Features are highly correlated
- You want feature selection but also want better handling of correlated predictors.

Formula:
![[Pasted image 20260824181545.png]]
![[Pasted image 20260824181615.png]]
![[Pasted image 20260824181633.png]]

**Working:**
Start with training data
		↓
  Calculate predictions
		↓
Calculate prediction error
		↓
Calculate L1 penalty
		↓
Calculate L2 penalty
		↓
  Combine all terms
	    ↓
  Optimize coefficients
		↓
Some coefficients may become zero while other are shrunk

- Elastic Net combines L1 and L2 regularization. The L1 component enables feature selection by making some coefficients exactly zero, while the L2 component improves stability when predictors are correlated.

Simplified:
                 ELASTIC NET
                     ↓
              Linear Regression
                     ↓
              Add Regularization
                  ↙       ↘
                L1           L2
                ↓              ↓
        Feature Selection    Stability
                ↘             ↙
                  Combined
                     ↓
               Shrink Coefficients
                     ↓
               Some → Exactly 0
                     ↓
       Reduce Overfitting + Multicollinearity