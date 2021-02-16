# competition-AMF
Compétition avec les données de l'Authorité des Marchés Financiers. 
Il s'agit de détecter les traders haute fréquence (HFT).

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
