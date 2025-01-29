# Classification Challenge

## Comparison of Logistic Regression vs Random Forest Classifier Model Prediction 

### Dataset 

* The data is located at [https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv](https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv)

* Dataset Source: [UCI Machine Learning Library](https://archive.ics.uci.edu/dataset/94/spambase)


### Initial Prediction 

Initial prediction before running the models it seemed Logistic Regression will perform well compared to the Random Forest Classifies because of binary nature of the labeled data.


### After Running the both models 

* Logistic Regression: Accuracy Score - 0.9278887923544744

* Random Forest Classifier: Accuracy Score - 0.9669852302345786

The accuracy score from RandomForestClassifier is 0.9669852302345786 which looks better than the LogisticRegression accuracy score of 0.9278887923544744. Based on the score RandomForestClassifier performed better than LogisticRegression, proving my initial guess is wrong. The reasons might be because there is an imbalance in y value counts, missing values in the dataset or large number of features.