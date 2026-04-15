Classification is a type of supervised learning where the goal is to predict a discrete label (category/class) for given input data.

It answers the question - "Which category does this data belong to?"

Basic Idea:
In supervised learning:
- You are given labeled data (input + correct  output)
- The model learns a mapping:
	- Input (X) -> Output (Y)
	where,
	- X = Features (e.g., age, salary, pixels)
	- Y = Class labels (e.g., 0/1, A/B/C)

Types of Classification:
1. [[Binary Classification]]
2. [[Multi-class Classification]]
3. [[Multi-label Classification]]
4. [[Imbalanced Classification]]

Working:
1. Data Collection : Gather labeled dataset
2. Data Preprocessing : Handle missing values
				    Normalize data
				    Encode Categorical values
3. Feature Selection : Choose important features
4. Model Training : Use classification algorithm
5. Prediction : Model predicts class labels
6. Evaluation : Check accuracy and other metrics

Popular Classification Algorithms:
1. [[Logistic Regression]]
2. [[Decision Tree]]
3. [[Random Forest]]
4. [[K-Nearest Neighbors]]
5. [[Support Vector Machine]]
6. [[Naive Bayes]]
7. [[Neural Networks]]

Evaluation Metrics for Classification:
1. [[Accuracy]]
2. [[Confusion Matrix]]
3. [[Precision]]
4. [[Recall]]
5. [[F1 Score]]
6. [[ROC Curve & AUC]]
7. [[Specificity]]

Overfitting & Underfitting:
Overfitting:
- Model learns training data too well
- Poor performance on new data
Underfitting:
- Model too simple
- Cannot learn patterns properly 

Bias - Variance Tradeoff
- High Bias -> Underfitting
- High Variance -> Overfitting

