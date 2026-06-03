- Used for classification, text classification, spam detection, sentiment analysis, document categorization
- It is based on Bayes' Theorem and assumes all features are independent of each other.
- 'Naïve Bayes is a probabilistic classification algorithm based in Bayes' Theorem that predicts the class of a data point by calculating probabilities under the assumption that features are independent.'

![[Pasted image 20260602211730.png]]

 P(A|B) -> Posterior probability. Probability of A given B
 P(B|A) -> Likelihood. Probability of B given A
 P(A) -> Prior probability. Probability of A before observing B
 P(B) -> Evidence. Total probability of B

Working: 
1. Collect training data
2. Calculate prior probabilities
3. Calculate conditional probabilities
4. Apply Bayes Formula
5. Choose highest probability

Types:
1. Gaussian Naïve Bayes: Used for continuous numerical data
2. Multinomial Naïve Bayes: Used for count data like in text classification and spam detection
3. Bernoulli Naïve Bayes: Used for [[Binary Classification]]

Advantages:
- Simple and easy
- Fast Training
- Fast Prediction
- Works well for Text Classification
- Requires less training data

Disadvantages:
- Strong independence assumption
- [[Zero Probability Problem]] -> Solution [[Laplace Smoothing]]
- Lower accuracy for complex relationships