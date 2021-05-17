# Diabetes-Classification

Basic implementation of different classifiers for predicting whether a patient has diabetes or not. This is simple binary classification based on the `pima-indian-diabetes-dataset` found on Kaggle. You can find the dataset [here](https://www.kaggle.com/uciml/pima-indians-diabetes-database).

### Classifiers used

Experimented with the following classifiers:

- SVM
- Random Forest
- Logistic Regression
- Naive Bayes
- AdaBoost
- Gradient Boosting

Also played around cleaning and standardizing the dataset.

### Prerequisites

- python-2.7.11
- scikit-learn
- numpy
- pandas


### How to Run

- Clone the repository
- Run the file corresponding to the classifier you want.
  - For SVM: `python svm.py`
  - For Ada Boost: `python ada_boost.py`
  - For Gradient Boost: `python grad_boost.py`
  - For Naive Bayes: `python naive_bayes.py`
  - For Random Forest: `python random_forest.py`
  - For Logistic Regression: `python log_reg.py`
