# mnist
Building models to predict MNIST data. Documentation has been listed here(https://docs.google.com/document/d/14kHFEqv503kohv5qBCwNiJqbxQc8iK1kqgYWXRBjnHo/edit?usp=sharing).

# Conventions
Data files must be inside input subdirectory.

Modeling scripts must be inside scripts subdirectory.

Modeling scripts must be named <MODELING TECHNIQUE>_<MODELING IMPLEMENTATION METHOD>.ipynb. For example, if we used random forest from sklearn, the script must be named randomforest_sklearn.ipynb. If we used dnn from tensorflow, the script must be named dnn_tensorflow.ipynb.
  
Once they are uploaded to kaggle, the scripts could be named differently.

The method used, the link to the script uploaded to kaggle, as well as the validation score, must be updated in the documentation.

Submission files must be named submission_<SCRIPT NAME>.csv
Kaggle scripts must be named <PROJECT NAME>(which is mnist here) <MODELING TECHNIQUE> <MODELING IMPLEMENTATION METHOD> < Validation score : > 
NOTE : We do not include test score as that is calculated only at the end to avoid overfitting to test data.
