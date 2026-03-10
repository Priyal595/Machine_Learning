# Types of Machine Learning

Machine Learning algorithms can be broadly classified based on how they learn from data. The three main types of Machine Learning are:

1. Supervised Learning  
2. Unsupervised Learning  
3. Reinforcement Learning  

---

## 1. Supervised Learning

Supervised Learning is a type of Machine Learning where the model is trained using **labeled data**.

This means the dataset contains both:
- **Input features (X)**
- **Correct output labels (Y)**

The goal of the model is to learn the relationship between the input and output so that it can predict the correct output for new unseen data.

### Common Supervised Learning Algorithms

- Linear Regression
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Trees
- Random Forest
- Support Vector Machines (SVM)
- Neural Networks

### Applications

- Email spam detection
- House price prediction
- Image classification
- Credit risk prediction

---

## 2. Unsupervised Learning

Unsupervised Learning is used when the dataset **does not contain labeled outputs**.

The model tries to discover **hidden patterns, structures, or relationships** within the data.

Instead of predicting outputs, the algorithm groups or organizes the data.

### Example

A company has customer data but no categories.  
The algorithm groups customers based on purchasing behavior.

### Common Unsupervised Learning Algorithms

- K-Means Clustering
- Hierarchical Clustering
- DBSCAN
- Principal Component Analysis (PCA)
- Autoencoders

### Applications

- Customer segmentation
- Market basket analysis
- Anomaly detection
- Data compression

---

## 3. Reinforcement Learning

Reinforcement Learning is a type of Machine Learning where an **agent learns by interacting with an environment**.

The agent takes actions and receives **rewards or penalties**. Over time, the agent learns which actions produce the best results.

### Key Components

- **Agent** – the learner or decision maker  
- **Environment** – the system the agent interacts with  
- **Action** – what the agent can do  
- **Reward** – feedback from the environment  

### Example

Training a robot to walk:
- If it walks successfully → reward
- If it falls → penalty

The robot gradually learns the best walking strategy.

### Applications

- Game playing (Chess, Go)
- Robotics
- Autonomous driving
- Recommendation systems
- Resource management