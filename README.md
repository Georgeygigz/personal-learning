# Machine Learning

- The science of getting machine act without explicitly being programmed
  Tom Mitchell provides a more modern definition: "A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E."

## Major Categories of ML Algorithms

### Supervised Learning

- In supervised learning we are given and already know what our correct output should look like, having the idea that there is a relationship between the input and the output.
- With labels
- Supervised learning is categorized into
- algorithms used include `Regression`, `KNN`, `Decision tree`, `Random Forest`

#### Regression

- We are trying to predict results within a continuous output,

#### Classification

- Predicting variables in a discrete output

### UnSupervised Learning

- No labels, no defined output/little ideas of what our results should look like
- Clustering algorithm is the one that is mostly used in Unsupervised learning
- There is no feedback based on prediction results
- Example of clustering, cocktail party problem
- octave/matlab programming environment, is a software used to implement algorithms(Prototype an algorithm)
- algorithms used include `Apriori algorithm`, `k-means`

### Reinforcement Learning

- rewards
- the machine is trained to make specific decisions
- the machine is exposed to an environment where it trains itself continually using trial and error
- this machine learns from past experience and tries to capture the best possible knowledge
- algorithms used is `markov Decision Process`

## ML Learning algorithms

### Linear regression/(Supervised learning)

#### Process

- Training set >> Learning algorithm >> h(hypothesis)
- hypothesis ie the function that takes in the input(x, size of the house) tries to output the estimated value(, cost of the house)
- hypothesis (h) maps (x) to (y)
- decide how to represent hypothesis h(x) =mx+c

#### Cost function example

- cost function is used to measure the accuracy of the hypothesis

##### Cost Function - Intuition II

- Looked into some values of the cost function and see how they correspond to hypothesis
- Next create an algorithm that automatically creates theta1 and theta0 that minimizes the cost function
- cost function maps the events of one or more variables onto a real number.
- Using the cost function in in conjunction with GD is called linear regression
- in "laymans" language cost function shows how much far away the predicted values are from the actual values
- Then for the intercept the value that produces the least error is the correct one.

#### Gradient decent

- is used for minimizing
- used not only in linear regression but also in all the place of ML
- in gradient decent as we approach the local minimum gradient decent automatically takes smaller steps
- one of the issues of gradient decent is it can be susceptible to local optimal.

##### Process

- we start with some (theta 0, theta 1)
- keep changing (theta 0, theta 1) to reduce J(theta 0, theta 1) until we end up at minimum

#### Gradient descent for linear Regression(Gradient decent and cost function) also known as "Batch" Gradient Descent

- apply gradient decent to minimize the the cost function
- cost function for linear regression is bowshaped(convex function), it doesn't have local optimal
- `Batch:` Each step of gradient decent uses all the training example.

#### Linear Algebra review

- Matrix is a rectangular array of numbers(nxm) n= rows, m= columns
- Vectors are matix that have only one column(nx1)
- Uppercase(Matrix), lower case(numbers, vector,scala)
- Scala is a real number

##### Properties of a matrix

- not commutative AxB != BxA apart from identity matrix
- associative property AxBxC=(AxB)xC=Ax(BxC)
- identity matrix have 1s along the diagonal and the rest are zeros 0

##### Special matrix operation

- `Matrix inverse` and `matrix transpose`

###### Matrix inverse

- 1 = identity matrix
- matrix A(A-inverse) = identity matrix
- None square matrix does not have inverse
- Matrices that don't have an inverse are singular or degenerate.

###### Matrix transpose

- A =mxn and A-transpose=B then B will be nxm

### multivariate regression

- Feature Scaling is
- Make sure features are on a similar scale
- Feature scaling involves dividing the input values by the range (i.e. the maximum value minus the minimum value) of the input variable, resulting in a new range of just 1
- Mean normalization involves subtracting the average value for an input variable from the values for that input variable resulting in a new average value for the input variable of just zero. To implement both of these techniques,

### Features and Polynomial Regression

- polynomial regression is the closely related idea of choosing features
- polynomial regressions used to change the behaviour of a curve(eg from linear to a curve)

### Normal equation
- will help solve the value of theta analytically

