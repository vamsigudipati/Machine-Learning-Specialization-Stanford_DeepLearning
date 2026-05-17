# Machine Learning Specialization — Stanford & DeepLearning.AI

My coursework and assignments for the [Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction) offered by Stanford University and DeepLearning.AI on Coursera (instructed by Andrew Ng).

The specialization consists of three courses covering supervised learning, advanced neural network techniques, and unsupervised/reinforcement learning.

---

## Courses

### Course 1 — Supervised Machine Learning: Regression and Classification

| Week | Content | Notebooks |
|------|---------|-----------|
| Week 1 | Python & Jupyter basics, model representation, cost function, gradient descent | `C1_W1_Lab01` – `C1_W1_Lab04` |
| Week 2 | NumPy vectorization, multiple-variable regression, feature scaling, polynomial regression, scikit-learn (GD & normal equation) | `C1_W2_Lab01` – `C1_W2_Lab06` |
| Week 3 | Classification, sigmoid function, decision boundary, logistic loss, logistic cost function, gradient descent for logistic regression, scikit-learn, overfitting, regularization | `C1_W3_Lab01` – `C1_W3_Lab09` |

---

### Course 2 — Advanced Learning Algorithms

| Week | Content | Notebooks |
|------|---------|-----------|
| Week 1 – Labs | Neurons & layers (TensorFlow), coffee-roasting neural network (TF & NumPy) | `C2_W1_Lab01` – `C2_W1_Lab03` |
| Week 1 – Assignment | Neural network for binary classification (handwritten digit recognition) | `C2_W1_Assignment` |
| Week 2 – Labs | Softmax activation, ReLU, multiclass classification (TF), backpropagation, derivatives | `C2_W2_SoftMax`, `C2_W2_Relu`, `C2_W2_Multiclass_TF`, `C2_W2_Backprop`, `C2_W2_Derivatives` |
| Week 2 – Assignment | Multiclass neural network (digit recognizer — 10 classes) | `C2_W2_Assignment` |
| Week 3 – Labs | Model evaluation & selection, diagnosing bias and variance | `C2W3_Lab_01`, `C2W3_Lab_02` |
| Week 3 – Assignment | Advice for applying machine learning (bias/variance, regularization, learning curves) | `C2_W3_Assignment` |
| Week 4 – Labs | Decision trees, tree ensembles (random forests & XGBoost) | `C2_W4_Lab_01`, `C2_W4_Lab_02` |
| Week 4 – Assignment | Decision tree implementation from scratch | `C2_W4_Decision_Tree_with_Markdown` |

---

### Course 3 — Unsupervised Learning, Recommenders & Reinforcement Learning

| Week | Content | Notebooks |
|------|---------|-----------|
| Week 1 – Assignment 1 | K-Means clustering (image compression) | `C3_W1_KMeans_Assignment` |
| Week 1 – Assignment 2 | Anomaly detection | `C3_W1_Anomaly_Detection` |
| Week 2 – Lab | PCA & data visualization | `C3_W2_Lab01_PCA_Visualization_Examples` |
| Week 2 – Assignment 1 | Collaborative filtering recommender system | `C3_W2_Collaborative_RecSys_Assignment` |
| Week 2 – Assignment 2 | Deep learning–based recommender system (neural network) | `C3_W2_RecSysNN_Assignment` |
| Week 3 – Lab | State-action value function example | `State-action value function example` |
| Week 3 – Assignment | Deep Q-Learning — Lunar Lander | `C3_W3_A1_Assignment` |

---

## Tech Stack

- **Python 3**
- **TensorFlow / Keras**
- **NumPy, Pandas, Matplotlib**
- **scikit-learn**
- **Jupyter Notebooks**

---

## Repository Structure

```
Machine-Learning-Specialization-Stanford_DeepLearning/
├── Supervised_Machine_Learning/
│   ├── Week1/          # Python basics, model representation, cost function, gradient descent
│   ├── Week2/          # Vectorization, multi-variable regression, feature scaling, sklearn
│   └── Week3/          # Logistic regression, classification, regularization, overfitting
├── Advanced_Learning_Algorithms/
│   ├── Week1_Labs/     # Neurons, layers, TF coffee-roasting demo
│   ├── Week1_Assignment/
│   ├── Week2_Labs/     # Softmax, ReLU, multiclass, backprop
│   ├── Week2_Assignment/
│   ├── Week3_Labs/     # Model evaluation, bias-variance
│   ├── Week3_Assignment/
│   ├── Week4_Labs/     # Decision trees, tree ensembles
│   └── Week4_Assignment/
└── Unsupervised_Learning_Recommenders_Reinforcement_Learning/
    ├── Week1_Assignment1/   # K-Means clustering
    ├── Week1_Assignment2/   # Anomaly detection
    ├── Week2_Lab/           # PCA visualization
    ├── Week2_Assignment1/   # Collaborative filtering
    ├── Week2_Assignment2/   # Neural-network recommender
    ├── Week3_Lab/           # State-action value function
    └── Week3_Assignment/    # Deep Q-Learning (Lunar Lander)
```
