# Credit-Card-Fraud-Detection
The Credit Card Fraud Detection Problem includes modeling past credit card transactions with the knowledge of the ones that turned out to be fraud. This model is then used to identify whether a new transaction is fraudulent or not. The aim here is to detect 100% of the fraudulent transactions while minimizing the incorrect fraud classifications. It was achieved using the dataset obtained from Kaggle (https://www.kaggle.com/mlg-ulb/creditcardfraud). 

The project is also being assessed using several other classification methods. As of now, I have used two methods.


## 1. Using Anomaly Detection Classifiers
I performed data preprocessing, performed exploratory data analysis and calculated the accuracy of the algorithms using anomaly detection models such as Local Outlier Factor (LOF) and Isolation Tree Classifier. Accuracy observed in both LOF and Isolation Tree Classifier are 99.65% and 99.77% respectively.

## 2. Using Classification Methods and SMOTE
Imbalanced classification involves developing predictive models on classification datasets that have a severe class imbalance. The challenge of working with imbalanced datasets is that most machine learning techniques will ignore, and in turn have poor performance on, the minority class, although typically it is performance on the minority class that is most important. One approach to addressing imbalanced datasets is to oversample the minority class, which is the Synthetic Minority Oversampling Technique (SMOTE). The objective in this project is to build machine learning models to classify or identify fraudulent card transactions from a given card transactions data. In this method, I have used Classification Algorithms (Random Forest, Decision Tree, Logistic Regression, KNN, Linear SVM, Naive Bayes Classifier) to perform fraud detection in the same dataset along with the SMOTE analysis.
The accuracy of the classifiers are as follows:
a) Random Forest = 100%
b) Decision Tree = 100%
c) Logistic Regression = 95.6%
d) KNN = 100%
e) Linear SVM = 95.3%
f) Naive Bayes Classifier = 91.9%

## 3. Credit Card Fraud Detection Using Classification Methods and SMOTE with RandomUnderSampler
In this exercise, we have performed oversampling and undersampling of the same classes using the RandomUnderSampler class from the imbalanced-learn library.
We can update the example to first oversample the minority class to have 10 percent the number of examples of the majority class, then use random undersampling to reduce the number of examples in the majority class to have 50 percent more than the minority class.
The accuracy of the classifiers are as follows:
a) Random Forest = 100%
b) Decision Tree = 100%
c) Logistic Regression = 96.3%
d) KNN = 99.8%
e) Linear SVM = 96.0%
f) Naive Bayes Classifier = 93.89%
