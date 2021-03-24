# Logistic Regression

Logistic Regression (also called Logit Regression) is commonly used to estimate the probability that an instance belongs to a particular class(e.g., what is the probability that this email is spam?). If the estimated probability is greater than 50%, then the model predicts that the instance belongs to that class (called the positive class, labeled “1”), or else it predicts that it does not (i.e., it belongs to the negative class, labeled “0”). This makes it a binary classifier. The Logistic Regression model also can be generalized to support multiple classes directly, without having to train and combine multiple binary classifiers. This is called Softmax Regression, or Multinomial Logistic Regression.

There are perhaps common four main types of classification tasks:

<ul>
<li>Binary Classification</li>
<li>Multi-Class Classification</li>
<li>Multi-Label Classification</li>
<li>Imbalanced Classification</li>
</ul>


In Logistic Regression, sigmoid function is commonly used, it is a way to convert predictions to a probabilitics perspective.

Popular algorithms that can be used for binary classification include:

Logistic Regression
k-Nearest Neighbors
Decision Trees
Support Vector Machine
Naive Bayes

Some algorithms are specifically designed for binary classification and do not natively support more than two classes; examples include Logistic Regression and Support Vector Machines.

Popular algorithms that can be used for multi-class classification include:

k-Nearest Neighbors.
Decision Trees.
Naive Bayes.
Random Forest.
Gradient Boosting.


## Limitation
1) Logistic regression is only effective when a linear classifier can easily distinguish between class 1 and 0.
2) Logistic regression maps the feature vectore to a single real-valued number, while multilayer perceptron maps the feature vector to multiple real-valued numbers.