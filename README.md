# Spam Detector - machine learning models to detect spam 
## summary

---
Data set: [Spambase Data Set](https://archive.ics.uci.edu/ml/datasets/spambase)

---
### Objectives
- Testing multiple machine learning models to predict whether a certain email is spam or not; 
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

| Model | Precision | K-fold Cross Validation | Repeated K-fold |
|-------|:-----------:|:-----------:|:-----------:|
| Logistic regression | 93.43% | 92.55%| 92.83% |
| Naive Bayes| | | | |
| --- Gaussian | 83.09% | | |
| --- Multinomia | 80.44%| | |
| --- Bernoulli | 87.54 | | |
| Random Forest | ~94.92% | | |