# Spam Detector - machine learning models to detect spam 
## summary

---
Data set: [Spambase Data Set](https://archive.ics.uci.edu/ml/datasets/spambase)

Notebooks (nbviewer):
- [00 summary](https://nbviewer.org/github/filipecfv/email-spam-detector/blob/main/00-summary.ipynb)
- [01 Exploratory Analysis](https://nbviewer.org/github/filipecfv/email-spam-detector/blob/main/01-Exploratory.ipynb)
- [02 Logistic Regression](https://nbviewer.org/github/filipecfv/email-spam-detector/blob/main/02-Logistic-regression.ipynb)
- [03 Naive Bayes](https://nbviewer.org/github/filipecfv/email-spam-detector/blob/main/03-Naive-bayes.ipynb)
- [04 Random Forest](https://nbviewer.org/github/filipecfv/email-spam-detector/blob/main/04-Random-Forest.ipynb)
- [05 Improving the model](https://nbviewer.org/github/filipecfv/email-spam-detector/blob/main/05-Improving-the-model.ipynb)

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
