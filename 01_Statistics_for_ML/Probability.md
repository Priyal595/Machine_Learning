# Probability

Probability is a branch of mathematics that measures the **likelihood of an event occurring**.  
It plays a fundamental role in Machine Learning because many models rely on probabilistic reasoning to make predictions.

---

## What is Probability?

Probability quantifies how likely an event is to occur.

The value of probability always lies between **0 and 1**.

- **0** → The event will never happen  
- **1** → The event will always happen  

Example:

If the probability of rain tomorrow is **0.7**, it means there is a **70% chance of rain**.

---

## Basic Probability Formula

Probability of an event \(A\):

\[
P(A) = \frac{\text{Number of favorable outcomes}}{\text{Total number of possible outcomes}}
\]

### Example

Rolling a six-sided die:

Probability of getting a **3**:

\[
P(3) = \frac{1}{6}
\]

Probability of getting an **even number**:

\[
P(\text{even}) = \frac{3}{6} = 0.5
\]

---

## Important Probability Terms

### Experiment
An action that produces outcomes.

Example:  
Rolling a die.

### Outcome
A possible result of an experiment.

Example:  
1, 2, 3, 4, 5, 6 when rolling a die.

### Event
A set of outcomes.

Example:  
Getting an even number.

---

## Conditional Probability

Conditional probability measures the probability of an event **given that another event has already occurred**.

Formula:

\[
P(A|B) = \frac{P(A \cap B)}{P(B)}
\]

Example:

Probability that a student passes an exam **given that they studied**.

---

## Bayes' Theorem

Bayes' theorem describes how to update the probability of a hypothesis based on new evidence.

\[
P(A|B) = \frac{P(B|A)P(A)}{P(B)}
\]

This theorem is widely used in Machine Learning algorithms such as **Naive Bayes classifiers**.

---

## Probability in Machine Learning

Probability helps ML models:

- Handle uncertainty in data
- Make predictions with confidence levels
- Model random variables
- Learn patterns from noisy datasets

Examples in ML:

- Naive Bayes classifier
- Bayesian networks
- Hidden Markov Models
- Probabilistic graphical models

---

## Example in Machine Learning

Suppose we want to classify an email as **spam or not spam**.

The model calculates:

- Probability that the email is spam given certain words
- Probability that the email is not spam

The class with the **higher probability** is chosen.

---

## Summary

Probability provides the mathematical foundation for many Machine Learning algorithms.  
It allows models to reason about uncertainty and make predictions based on observed data.