- Intelligent [[Hyperparameter Tuning]] technique that finds the best hyperparameters using the results of previous trials.
- 'Bayesian Optimization is a smart search algorithm that uses probability to find the best hyperparameters with fewer training runs.'

Basic Workflow:
Choose Initial Hyperparameters
    ↓
Train Model
    ↓
Measure Performance
    ↓
Build Probabilistic Model
    ↓
Predict Best Next Trial
    ↓
Train Again
	↓
Update Model
    ↓
Repeat

Key Components:
1. Surrogate Model :  Approximates the true objective function.
		Hyperparameter -> Expected Performance
		Most commonly : 
		- Gaussian process (GP) 
		- Tree-Structured Parzen Estimator (TPE)
2. Acquisition Function : Decides where to search next.
		Common Acquisition functions:
		- Expected Improvement (EI): Selects points expected to improve current best results.
		- Probability of Improvement (PI): Chooses points likely to beat the current best.
		- Upper Confidence Bound (UCB): Balances Performance -> Uncertainty

Advantages:
- Efficient
- Faster
- Better Search
- Handles continuous parameters
- Works well for [[Deep Learning]]

Disadvantages:
- More complex
- Computational Overload
- Less effective in extremely high dimensions

Popular Libraries:
- Optuna
- Hyperopt
- Scikit-Optimize
- BoTorch


