# XGBOOST
XGBOOST is a boosting technique used in machine learning

When to use XGBOOST:
- large number of training samples: Greater than 1000 training samples and less than 100 features
- the number of features < number of training samples
- mixture of categorical and numerical features
- Just numerical features

When not to use XGBOOST and use deep learning instead : 
- Image classification
- NLP

Use of one hot encoding on categorical data

# one hot encoding:
- convert categorical data into multiple columns of binary values.

One hot encoding using either get_dummies() or ColumnTransformer()

One hot encoding is not for linear regression but works great with decision trees.


