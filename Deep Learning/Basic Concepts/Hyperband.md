- It is a [[Hyperparameter Tuning]] algorithm designed to find good hyperparameter settings while using much less computational time than Grid Search and Random Search.
- 'Hyperband trains many hyperparameter configurations for a short time, quickly discards poor performers, and allocates more resources only to promising ones.'
- Think of it as a **Knockout Tournament for hyperparameters**.
- Main concept used is resource allocation.
- Hyperband is based on an algorithm called 'Successive Halving'.

Workflow:
Generate Configurations
      ↓
Train Briefly
	  ↓
Evaluate
     ↓
Remove Weak Models
     ↓
Increase Resources
	 ↓
Evaluate Again
    ↓
Repeat
    ↓
Best Hyperparameters

Successive Halving Steps:
1. Train many configurations briefly.
2. Evaluate performance.
3. Remove worst performers.
4. Allocate more resources to survivors.
5. Repeat


Key Hyperband Parameters:
1. Maximum Resource (R): Maximum training budget.
2. Reduction factor (η): Controls elimination rate.

Advantages:
- Very fast
- Saves computation
- Works well for [[Deep Learning]]
- Scalable
- Simple

Disadvantages:
- May eliminate good models early
- Requires resource definition
- not always better than [[Bayesian Optimization]]

Popular Libraries:
- Ray Tune
- Keras Tuner
- Optuna