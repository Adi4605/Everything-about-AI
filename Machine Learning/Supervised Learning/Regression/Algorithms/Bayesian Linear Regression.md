- Probabilistic version of Linear Regression
- Model treats its unknown parameters-such as weights and intercept-not as fixed unknown numbers, but as random variables with probability distributions.
- Combines linear regression with [[Bayes' theorem]] to estimate a probability distribution over the model parameters and make predictions with uncertainty.
- It combines: Prior knowledge 
			Observed data
- Produces a posterior distribution for the model parameters

**Start with a prior belief, update it using observed data, and obtain a posterior belief.**

**Working:**
	     Data
           ↓
    Define Linear Model
           ↓
     Choose Prior
           ↓
    Define Likelihood
          ↓
Perform Bayesian Inference
          ↓
Obtain Posterior Distribution
         ↓
   Estimate Parameters
         ↓
  Predictive Distribution
        ↓
Prediction + Uncertainty

- Prior Belief -> initial assumption or probability about something before you see a new evidence
- Posterior Belief -> updated probability after you factor in that new data
- Likelihood -> Describes how predictable the observed data is for a particular set of parameters.

- Posterior Mean and Variance:
	For common conjugate Bayesian Linear Regression, the posterior of β is Gaussian:
		![[Pasted image 20260824165833.png]]
		![[Pasted image 20260824165848.png]]


Simplified:
BAYESIAN LINEAR REGRESSION
     ↓
Linear Model
     ↓
Parameters treated as Random Variables
     ↓
Choose Prior
     ↓
Observe Data
     ↓
Likelihood
     ↓
Bayes' Theorem
     ↓
Posterior Distribution
     ↓
Prediction Distribution
     ↓
Prediction + Uncertainty