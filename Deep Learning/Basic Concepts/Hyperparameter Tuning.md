- 'Hyperparameter Tuning is the process of selecting the best hyperparameter values before training a machine learning model.'
- Hyperparameters : Settings that are chosen before training begins. They control how the model learns.
 - ![[Pasted image 20260615172537.png]]

Workflow:
Choose Hyperparameters
          ↓
Train Model
          ↓
Evaluate Model
          ↓
Adjust Hyperparameters
          ↓
Retrain Model
          ↓
Best Performance

Methods:
1. Manual Search: Try each value manually. Easy but time-consuming and not practical for many hyperparameters
2. Grid Search: Try every possible combination. Finds good combinations but computationally expensive
3. Random Search: Instead of checking all combinations, select random combinations. Faster than grid search and often performs surprisingly well but may miss optimal combination.
4. [[Bayesian Optimization]]
5. [[Hyperband]]
6. [[Evolutionary Algorithms]]

Advantages:
- Better accuracy
- Better generalization
- Reduces overfitting 
- Optimizes Resource Usage

Disadvantages:
- Computational cost
- Time consuming
- Complex for [[Deep Learning]]
