# Codsoft_task_no.3
Credit Card Fraud Detection Model

Link to the data set as it is quite heavy to upload here: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Objective:
  Build a machine learning model to identify fraudulent credit card transactions. 
  Preprocess and normalize the transaction data, handle class 
  imbalance issues, and split the dataset into training and testing sets.
  Train a classification algorithm, such as logistic regression or random forests, to classify transactions as fraudulent or genuine.
  Evaluate the model's performance using metrics like precision, recall,and F1-score, and consider techniques like oversampling or
  undersampling for improving results.

  Highlights:
  1. Dataset does not contain any null values but it is sure there must be some duplicate values which we will look into moving further.
  2. The data set contains two data types i.e. float, and integer.
  3. Class is the only column having integer values.
  4. 473 values are Fraud against 283253
  5. majority of fraud is in the range of 20 dollars
  6. Amount and Class show a negative correlation among the data from v1 to v-18 approximately
  7. Use undersampling techniques to see a better picture of correlations
  8. there is a strong correlation between class, v4, v11 and v2 columns
  9. Applied SMOTE resampling technique for better distribution of various featured
  10. Used this resampled dataset and split it into train and test dataset
  11. Applied LOGISTIC REGRESSION model and get a accuracy score
  12. We test our model accuracy using confusion matrix, precision score, Recall score and F1 score WHICH COMES TO BE 0.9 which shows that our model is quiet efficient in predicting the fraud cases.

Here I end my project . Hope you all like it. All feedbacks are welcome. Thanks :)
