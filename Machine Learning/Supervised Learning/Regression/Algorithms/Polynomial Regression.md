- used to model a nonlinear relationship between an independent variable and a continuous dependent variable by using polynomial powers of the input features
- Polynomial Regression is often implemented as:
	Polynomial Feature Transformation + Linear Regression
Formula:
For a general degree-d polynomial:
	![[Pasted image 20260824193515.png]]
	![[Pasted image 20260824193354.png]]

Working:
Dataset
   ↓
Data Preprocessing
   ↓
Select Features
   ↓
Train/Test Split
   ↓
Generate Polynomial Features
   ↓
Train Linear Regression
   ↓
Make Predictions
   ↓
Evaluate Model

- Degree is a hyperparameter
- Evaluated using validation/cross-validation
- [[Feature Explosion]] can happen

Simplified:
              POLYNOMIAL REGRESSION
                       ↓
                  Start with X
                       ↓
            Generate Polynomial Features
                       ↓
                X, X², X³, ... Xᵈ
                       ↓
              Apply Linear Regression
                       ↓
                Learn Coefficients
                       ↓
                Make Prediction
                       ↓
               Evaluate Performance