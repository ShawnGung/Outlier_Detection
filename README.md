# Outlier Dection

# environment
- python
- numpy

# result
- in supervised machine learning algorithms, combining different classifiers(random forest,adaboost,logistic regression) would have a much more robust model when facing the new data.
- in unsupervised algorithm like OneClassSVM, we fit the model with white list(normal data) , and find a hyper ball to contain all the normal data.When tesing, if new data is outside the ball, we could say it properly would be Outlier point(abnormal data).However, this algorithm would have high recall and low precision in terms of abnormal data.
