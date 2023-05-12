# Spam Detector - machine learning models to detect spam 
## summary

---
Data set: [Spambase Data Set](https://archive.ics.uci.edu/ml/datasets/spambase)

---
### Objectives
- Testing multiple machine learning models to detect whether a certain email is spam or not; 
- Validating each model to minimize randomness; 

---
### Machine Learning models used in this notebook: 
- [x] Logistic regression
- [x] Naive Bayes
    - [x] Gaussian Naive Bayes
    - [x] Multinomia Naive Bayes
    - [x] Bernoulli Naive Bayes
- [x] Random Forest

--- 
### Results:

| Model | Initial Precision | K-fold Cross Validation | Repeated K-fold |
|-------|:-----------:|:-----------:|:-----------:|
| Logistic regression | 93.43% | 92.55%| 92.83% |
| Naive Bayes (Gaussian) | 81.84% | 81.77%| 81.67%|
| Naive Bayes (Multinomia) | 78.80% | 79.24% | 79.26% |
| Naive Bayes (Bernoulli) | 88.88% | 88.41% | 88.40% |
| Random Forest | 94.79% | 95.39% |  95.29% |