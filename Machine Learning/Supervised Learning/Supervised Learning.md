In Supervised Learning, model learns from labelled data - meaning every input has a corresponding correct output. 
The model make predictions and compares them with the true outputs, adjusting itself to reduce errors and improve accuracy over time.
The goal to make accurate prediction on new, unseen data.

![[Pasted image 20260316200817.png|546]]

Types of Supervised Learning : 
1. [[Classification]] : Where the output is categorical value.
2. [[Regression]] : Where the output is continuous variable.

While training the model, data is usually split in the ratio of 80:20 i.e. 80% is training data and rest is testing data. In training data we fill the input as well as output  for 80% data. The model learns from training data only.

Working of Supervised Machine Learning :
1. Collect Labeled Data : 
	- Gather a dataset where each input has a known correct output.
2. Split the Dataset :
	- Divide the data into training data (about 80%) and testing data (about 20%)
	- The model will learn from the training data and be evaluated on the testing data.
3. Train the Model :
	- Feed the training data(inputs and their labels) to a supervised learning algorithm.
	- The model tries to find patterns that map inputs to correct outputs.
4. Validate and Test the Model :
	- Evaluate the model using  testing data it has never seen before.
	- The model predicts outputs and these predictions are compared with the actual labels to calculate accuracy or error.
5. Deploy the Predict on New Data :
	- Once the model performs well, it can be used to predict outputs for completely new, unseen data.

Supervised Machine Learning Algorithms : 
1. [[Linear Regression]] : 
2. [[Logistic Regression]] :
3. [[Decision Tree]] :
4. [[Random Forest]] :
5. [[Support Vector Machine]] :
6. [[K-Nearest Neighbors]] :
7. [[Gradient Boosting]] :
8. [[Naive Bayes Algorithm]] :