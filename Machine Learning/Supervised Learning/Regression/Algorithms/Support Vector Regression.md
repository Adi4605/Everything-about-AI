- Supervised machine learning algorithm
- Regression version of Support Vector Machine (SVM)
- SVR finds a function that predicts continuous values while allowing errors within a specified tolerance and penalizing only errors outside that tolerance
- Tries to fit a function within an epsilon(ε) margin/tube around the data
- **ε-tube (epsilon-insensitive tube)** -> a margin of tolerance or a buffer zone built around the model's predicted regression line.

Formula for linear SVR:
    ![[Pasted image 20260824191131.png]]
	![[Pasted image 20260824191151.png]]

**Workflow:**
Dataset
   ↓
Data Cleaning
   ↓
Feature Selection
   ↓
Train/Test Split
   ↓
Feature Scaling
   ↓
Choose Kernel
   ↓
Choose C and ε
   ↓
Train SVR
   ↓
Make Predictions
   ↓
Evaluate

SVR Objective Function:
	![[Pasted image 20260824191222.png]]
subject to:
	![[Pasted image 20260824191248.png]]
where,
![[Pasted image 20260824191308.png]]

Important Hyperparameters:
1. **C** -> controls penalty for error outside the ε-tube
2. **ε** -> controls the width of the tolerance tube
		controls how much error is acceptable
3. **Kernel** -> Radial Basis Function (RBF)
4. **Gamma (γ)** for RBF/poly kernels

SVR Kernels:
1. Linear Kernel
2. Polynomial Kernel
3. RBF Kernel
4. Sigmoid Kernel

SVR Loss Function:
	![[Pasted image 20260824191651.png]]

Simplified:
                 SUPPORT VECTOR REGRESSION
                            ↓
                    Continuous Target
                            ↓
                    Create ε-Tube
                            ↓
	              Errors within ε → No Penalty
                            ↓
	            Errors outside ε → Penalized
                            ↓
	                  Important Points
                            ↓
                    Support Vectors
                            ↓
	               C → Penalty Strength
	               ε → Error Tolerance
	               γ → Point Influence
                            ↓
                  Kernel for Nonlinearity