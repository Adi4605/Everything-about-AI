- Supervised machine learning algorithm used to predict a continuous numerical value.
- Uses tree-like structure of questions/conditions to divide the dataset into smaller groups and then predicts a value for each final group
- predicts continuous values by recursively splitting the data into groups based on feature values and assigning a prediction to each final leaf node.

Components:
1. Root Node: root is the first splitting point.
2. Internal Node: it contains a decision/split
3. Branch: it represents the outcome of a decision
4. Leaf Node: it is the final node

- Uses the **mean target value** of training samples
- The algorithm tries different possible splits and chooses the one that produces the **largest reduction in prediction error/impurity**.
- Tree tries to minimize the within-leaf squared error
 ![[Pasted image 20260824195648.png]]

Workflow:
    Dataset
       ↓
Data Preprocessing
       ↓
Train/Test Split
       ↓
Choose Splitting Criterion
      ↓
Find Best Feature
      ↓
 Split the Dataset
      ↓
Recursively Split Again
      ↓
   Leaf Nodes
      ↓
Mean Target in Each Leaf
      ↓
   Prediction
      ↓
 Evaluate Model

The tree can stop based on conditions such as:
- Maximum depth reached
- Minimum number of samples required for splitting
- Minimum number of samples in a leaf
- Minimum impurity decrease
- No useful split remains
These are controlled by **hyperparameters**

Important Hyperparameters:
1. `max_depth`
2. `min_sample_split`
3. `min_samples_leaf`
4. `max_features`
5. `max_leaf_nodes`
6. `min_impurity_decrease`
7. `criterion`

Simplified:
DECISION TREE REGRESSION
          ↓
       Input Data
          ↓
   Find Best Feature/Split
          ↓
       Split Data
       ↙       ↘
 Group 1   Group 2
     ↓            ↓
    Split       Split
     ↓            ↓
        ...
         ↓
    Leaf Nodes
         ↓
    Mean Target Value
         ↓
      Prediction
