- Supervised machine learning algorithm used to predict a continuous numerical value
- It is an [[Ensemble Method]] that combines the predictions of many Decision Tree Regressors to produce a more accurate and stable prediction.

**Random Forest Regression builds many decision trees using different random samples and subsets of features, and combines their predictions-usually by averaging them-to obtain the final prediction.**

**Working:**
                   Dataset
                     ↓
                Train/Test Split
                     ↓
            Bootstrap Sampling
                     ↓
        ┌────────────┼────────────┐
	    ↓                      ↓                      ↓
	   Tree 1               Tree 2             Tree N
	    ↓                      ↓                      ↓
	Prediction         Prediction       Prediction
        └────────────┼────────────┘
                    ↓
                  Average
                     ↓
                Final Prediction
                     ↓
           MAE / RMSE / R² Evaluation

- Uses the concept of [[Bagging]] (Bootstrap Aggregating)
- [[Bootstrap Sampling]] -> Sampling with replacement

Important Hyperparameters:
1. `n_estimators`
2. `max_depth`
3. `max_features`
4. `min_samples_split`
5. `min_samples_leaf`
6. `max_leaf_nodes`
7. `bootstrap`
8. `criterion`

Simplified:
             RANDOM FOREST REGRESSION
                         ↓
                  Original Dataset
                         ↓
	               Bootstrap Sampling
                         ↓
	              Multiple Decision Trees
                         ↓
		       Random Feature Selection at Splits
                         ↓
	             Each Tree Makes Prediction
                         ↓
                  Average Predictions
                         ↓
	                Final Prediction