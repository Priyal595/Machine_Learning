# Bias vs Variance

Bias and Variance are two fundamental sources of error in Machine Learning models. Understanding their balance is essential for building models that generalize well to unseen data.

---

## Bias

Bias refers to the error introduced when a model makes **strong assumptions about the data**.  
A high-bias model is usually **too simple** and fails to capture the underlying patterns in the dataset.

### Characteristics

- Model is too simple
- Misses important patterns
- High training error
- Leads to **underfitting**

### Example

Using a **linear regression model** to fit data that actually follows a **complex nonlinear pattern**.

### How to Reduce Bias

- Use a more complex model
- Add more relevant features
- Reduce regularization
- Train the model longer

---

## Variance

Variance refers to how much the model's predictions **change when trained on different subsets of data**.

A high-variance model learns the training data very well but **does not generalize well to new data**.

### Characteristics

- Very low training error
- High test error
- Model captures noise in data
- Leads to **overfitting**

### Example

A very deep decision tree that memorizes the training data instead of learning general patterns.

### How to Reduce Variance

- Use more training data
- Apply regularization
- Use simpler models
- Use ensemble methods (Random Forest, Bagging)
- Apply cross-validation

---

## Bias–Variance Tradeoff

In Machine Learning, there is a tradeoff between bias and variance.

| Model Type    | Bias     | Variance | Result             |
|---------------|----------|----------|--------------------|
| Simple model  | High     | Low      | Underfitting       |
| Complex model | Low      | High     | Overfitting        |
| Balanced model| Moderate | Moderate | Good generalization|

The goal is to **find the right balance** so that the model performs well on both training and unseen data.

---

## Intuition

Imagine trying to hit the center of a target:

- **High Bias:** Always miss the target in the same direction
- **High Variance:** Hits are scattered all over the place
- **Balanced Model:** Hits close to the center consistently

---

## Goal in Machine Learning

The objective of model training is to **minimize total prediction error**, which is influenced by both bias and variance.

A good model should:

- Capture the true patterns in the data
- Avoid memorizing noise
- Generalize well to new unseen data