AMF DATA CHALLENGE(3rd but still running). 

Predict the high frequency traders for "autorité des marchés financiers" institution. Multiclass classification task

###########################################################################

HOW TO USE THIS?

    - download the dataset
    - launch the EDA and modeles files in a Jupyter environnement
    -  informations on the challenge : https://challengedata.ens.fr/participants/challenges/50/

##############################################################################

EDA file :
- overall shape
- NaNs visualisation
- features distribution
- features distribution for each class
- (features correlation)
- (visualisation 2d with a PCA : for fun)

Models file :
- different imputation strategies
- benchmark with different models (logistic regression, kNN, random forest, adaboost, xgboost)
- learning curves
- gridsearch et randomized search to optimize parameters
- (catboost try)

Neural network file : (attempt for fun in with keras) 
- target encoding
- callbacks/ dense layers/ dropout/ batchnormalization attempts
- learning curves
