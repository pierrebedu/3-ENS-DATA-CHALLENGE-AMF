# competition-AMF
Compétition avec les données de l'Authorité des Marchés Financiers. 
Il s'agit de détecter les traders haute fréquence (HFT).

Code needs cleaning.

###########################################################################

HOW TO USE THIS?

    download the dataset
    launch the EDA and modeles files in a Jupyter environnement

##############################################################################

EDA :
- visualisation des valeurs manquantes
- étude de la distribution des variables
- étude des liens features/target
- étude des corrélations entre features
- PCA pour visualiser le dataset dans le plan

Modèles :
- essais d'imputations
- comparaison de modèles (regression logistique, kNN, random forest, adaboost, xgboost)
- learning curves
- gridsearch et randomized search pour optimiser les hyperparamètres
- essai de catboost

Essai de réseau de neurones :
- encodage de la target
- callbacks/ dense layers/ dropout/ batchnormalization
- learning curves

Bon résultats sur la compétition à ce stade (1er).

Notes perso: pas encore essayés en gridsearch
-max_depth_trees (par defaut=6 donc de 1 à 5),   g
-gamma=0 (loss reduction minilale pour splitter (1-3-10, 30),
- tous learning rates entre 0 et 1 (pas 0.1), 

-random forest : max features et 300 arbres
