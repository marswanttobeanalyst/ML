# My diary of learning Machine Learning
My progress of learning Machine Learning. The notes, the tutorial and the projects.

## Supervised Learning
algorithms that learn x to y or input to output mappings. The key characteristic of supervised learning is that you give your learning algorithm examples to learn from.

### 1. Regression
algorithm learns to predict numbers out of infinitely many possible numbers. 

#### Linear Regression
fitting a straight line to your data. 
![difference](https://github.com/user-attachments/assets/2c43ca34-4995-4a4b-b4ed-fc8078b7d575)

##### Univariate Linear Regression (One-variable linear regression)
![1_lEy6nZXfCm9xBZ4WR8wqHw](https://github.com/user-attachments/assets/df2e4608-8e16-4b30-b76d-43ab973df76b)

###### Cost Function
The cost function, J(θ) measures the difference between the model's predictions and the actual true values for y. In linear regression, the goal is to find the optimal values for the parameters w and b that minimize this cost function. By minimizing J, we ensure that our model's predictions are as close as possible to the true values, thereby improving the accuracy of the model.

```math
\[ J(w, b) = \frac{1}{2m} \sum_{i=1}^{m} \left( \hat{y}^{(i)} - y^{(i)} \right)^2 \]
````


### 2. Classification
The learning algorithm has to make a prediction of a category, all of a small set of possible outputs or numbers.

## Unsupervised Learning
the data comes only with inputs x but not output labels y, and the algorithm has to find some structure or some pattern or something interesting in the data.

### 1. Classification
Algorithm that groups similar data points together based on their similar features.


### 2. Anomaly Detection

### 3. Dimensionality Reduction
