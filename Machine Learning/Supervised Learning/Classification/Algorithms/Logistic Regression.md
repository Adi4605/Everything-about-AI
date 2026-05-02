- Works best for linear classification
- It is used to **predict categories**, not continuous values
- Uses [[Sigmoid Function]] 
- Dependent variable is categorical or binary (0 or 1)
- It creates a decision boundary
- Instead of using Mean Squared Error, Log Loss/Binary Cross Entropy is used
- Needs gradient descent

Working:
1. Take input features (x)
2. Multiply by weights (w)
3. Add bias (b)
4. Apply sigmoid function
5. Get probability

- If probability >= 0.5 -> Class 1
- If probability < 0.5 -> Class 0

Types:
1. Binary Logistic Regression: Output = 0 or 1
2. Multinomial Logistic Regression: Output = Multiple Classes
3. Ordinal Logistic Regression: Output has order (like Low, Medium, High)

Assumptions of Logistic Regression:
- Data is linearly separable
- No multicollinearity
- Independent features
- Large datasets preferred