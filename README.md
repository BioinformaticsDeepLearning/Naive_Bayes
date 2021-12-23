# Naive_Bayes

Naive Bayes classifiers are a family of “probabilistic classifiers” based on Bayes’ theorem with strong independence between the features. They are among the simplest Bayesian network models and are capable of achieving high accuracy levels.

Bayes theorem states mathematically as:
P(A|B) = ( P(B|A) * P(A) )/ P(B)
where A and B are events and P(B) != 0.
P(A|B) is a conditional probability: the probability of event A occurring given that B is true.
P(B|A) is also a conditional probability: the probability of event B occurring given that A is true.
P(A) and P(B) are the probabilities of observing A and B respectively without any given conditions.
A and B must be different events.


How to implement Naive Bayes

Step 1: We start by importing dataset and necessary dependencies. ...
Step 2: Calculate Prior Probability of Classes P(y) ...
Step 3: Calculate the Likelihood Table for all features. ...
Step 4: Now, Calculate Posterior Probability for each class using the Naive Bayesian equation.
