# Overview

As part of this competition, we try to come up with a model for predicting MNIST data.

# Modeling techniques analyzed

  - [RandomForest](https://github.com/babinu-uthup-4JESUS/mnist/blob/master/scripts/randomforest_sklearn.ipynb) ([uploaded on kaggle](https://www.kaggle.com/babinu/mnist-random-forest-validation-score-0-965)) (Validation score : 96.5%)
  - [DNN using tensorflow](https://github.com/babinu-uthup-4JESUS/mnist/blob/master/scripts/dnn_tensorflow.ipynb) ([uploaded on kaggle](https://www.kaggle.com/babinu/mnist-dnn-tensor-flow-validation-score-0-976)) (Validation score : 96.5%)
  - [Logistic classifier (with sklearn)](https://github.com/babinu-uthup-4JESUS/mnist/blob/master/scripts/logistic_classification_sklearn.ipynb) ([uploaded on kaggle](https://www.kaggle.com/babinu/mnist-logistic-class-skl-val-score-0-916)) (Validation score : 96.5%)
  - [Logistic classifier (with tensorflow)](https://github.com/babinu-uthup-4JESUS/mnist/blob/master/scripts/logistic_classification_tensorflow.ipynb) ([uploaded on kaggle](https://www.kaggle.com/babinu/mnist-logistic-class-tfl-val-score-0-899)) (Validation score : 96.5%)
  - [Gradient boosting using xgboost](https://github.com/babinu-uthup-4JESUS/mnist/blob/master/scripts/boosting_trees_xgboost.ipynb) ([uploaded on kaggle](https://www.kaggle.com/babinu/mnist-boosting-trees-xgboost-val-score-0-9723?scriptVersionId=10007425)) (Validation score : 96.5%)
 
  

Now that we have these models, the natural step is to do an ensemble of the best models (checking their correlations in the process as well) and see how much of an improvement we get.

[We do an ensemble of randomForest, dnn and gradient boosting models and that does give us  an accuracy bump of 0.25% on the validation set.](https://github.com/babinu-uthup-4JESUS/mnist/blob/master/scripts/ensembler.ipynb)

The next step in this project would be to explore [convolutional neural networks](https://www.kaggle.com/cdeotte/25-million-images-0-99757-mnist), but I am putting that on hold for now, since my current priority is to master data exploration/validation methods and modeling techniques  that I am aware of (rather than always jumping on to new ones).

Hence, let us generate the predictions on the test set with our final ensembled model and submit them to kaggle.
