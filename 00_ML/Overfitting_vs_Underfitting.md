# Overfitting vs Underfitting

One of the most important concepts in Machine Learning is understanding **how well a model generalizes to unseen data**. Two common problems that occur during model training are **underfitting** and **overfitting**.

---

## Underfitting

Underfitting occurs when a model is **too simple to capture the underlying patterns in the data**.

The model fails to learn the relationship between input features and the target variable.

### Characteristics

- Poor performance on **training data**
- Poor performance on **test data**
- Model is too simple
- High bias

### Example

Trying to fit a **straight line** to data that follows a **complex curve**.

### Causes

- Model is too simple
- Insufficient training time
- Important features missing
- Too much regularization

### How to Fix Underfitting

- Use a **more complex model**
- Add more features
- Reduce regularization
- Train the model longer

---

## Overfitting

Overfitting occurs when a model **learns the training data too well**, including noise and small fluctuations.

The model performs very well on training data but **fails to generalize to new unseen data**.

### Characteristics

- Very good performance on **training data**
- Poor performance on **test data**
- Model memorizes training data
- High variance

### Example

A model that fits **every point in the dataset perfectly**, creating a very complex curve.

### Causes

- Model too complex
- Too many features
- Small dataset
- Training too long

### How to Fix Overfitting

- Use **more training data**
- Apply **regularization**
- Reduce model complexity
- Use **cross-validation**
- Use techniques like **dropout (in neural networks)**

---

## Visual Intuition

| Model Type | Description |
|------|------|
| Underfitting | Model too simple, cannot learn patterns |
| Good Fit | Model captures the true pattern |
| Overfitting | Model memorizes training data |

---

## Bias-Variance Relationship

Underfitting and overfitting are closely related to the **bias-variance tradeoff**.

| Problem     | Bias    | Variance |
|------       |------   |------    |
| Underfitting| High    | Low      |
| Overfitting | Low     | High     |
| Good Model  | Balanced| Balanced |

---

## Example in Real Life

Suppose we are predicting **house prices**.

- **Underfitting:** Model uses only house size to predict price.
- **Good fit:** Model uses size, location, number of rooms, and age.
- **Overfitting:** Model memorizes exact prices of training houses instead of learning patterns.

---

## Goal in Machine Learning

The goal is to build a model that **balances bias and variance**, so it performs well on both training and unseen data.

A well-trained model should **generalize well to new data** rather than memorizing the training dataset.