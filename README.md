# My diary of learning Machine Learning
My progress of learning Machine Learning. The notes, the tutorial and the projects.

## Supervised Learning
algorithms that learn x to y or input to output mappings. The key characteristic of supervised learning is that you give your learning algorithm examples to learn from.

### 1. Regression
algorithm learns to predict numbers out of infinitely many possible numbers. 

#### Linear Regression
fitting a straight line to your data. 

##### Univariate Linear Regression (One-variable linear regression)
![1_lEy6nZXfCm9xBZ4WR8wqHw](https://github.com/user-attachments/assets/df2e4608-8e16-4b30-b76d-43ab973df76b)
```math
ŷ = w \cdot x + b
```

###### Cost Function
The cost function, J(θ) measures the difference between the model's predictions and the actual true values for y. In linear regression, the goal is to find the optimal values for the parameters w and b that minimize the cost function, J. By minimizing J, we ensure that our model's predictions are as close as possible to the true values, thereby improving the accuracy of the model.

How to calculate Cost Function (Squared error Cost Function Formula):
```math
J(w, b) = \frac{1}{2m} \sum_{i=1}^{m} \left( \hat{y}^{(i)} - y^{(i)} \right)^2
````

###### Gradient Descent
an algorithm that you can use to try to minimize any function

```math
 w := w - \alpha \frac{1}{m} \sum_{i=1}^{m} \left( \hat{y}^{(i)} - y^{(i)} \right) x^{(i)}
```

```math
 b := b - \alpha \frac{1}{m} \sum_{i=1}^{m} \left( \hat{y}^{(i)} - y^{(i)} \right)
```

![Screenshot 2024-07-15 122010](https://github.com/user-attachments/assets/2aff0349-7709-4789-a59b-ca1d4524ee89)
applicable for parameter b as well

repeat until reach convergence (local minima)

### 2. Classification
The learning algorithm has to make a prediction of a category, all of a small set of possible outputs or numbers.

## Unsupervised Learning
the data comes only with inputs x but not output labels y, and the algorithm has to find some structure or some pattern or something interesting in the data.

### 1. Classification
Algorithm that groups similar data points together based on their similar features.


### 2. Anomaly Detection

### 3. Dimensionality Reduction
