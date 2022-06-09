# Machine-Deep-Learning-in-R
Construction d'un score d'octroi 

Le jeux de données provient d'un constructeur de véhicule ayant comme envie de construire un modèle de score d'octroi.

Le problème a été modifié de tel sorte à ce que l'on construise une probabilité de défaut en premier lieu pour obtenir un score de défaut puis un score d'octroi.

La plus grosse problématique étant le faible taux de cible (98 contrats défauts sur +9000 : 1% de taux cible)

Le clien demandait le benchmark suivant : 
- Utilisé Rstudio 
- Régression logistique  
- Courbe lift défaut et octroi

Le projet se décompose en plusieurs parties : 

I./ Pré traitement de données :
- Analyse descriptive
- Qualité des données (gestion des NA)
- Création de features à l'aide de la densité conditionnelle

II./ Split et Ré échantillonnage :
- Split des données en 2 data set : Train et Test
- Ré échantillonage car 1% de donnée cible 

III./ Régression Logistique :
- Création du modèle
- Validation du modèle : Lift et ROC

IV./ Random Forest : 
- Création du modèle
- Validation du modèle : Lift et ROC

V./ MultiLayer Perceptron (MLP) : 
- Création du modèle
- Validation du modèle : Lift et ROC

VI./ Analyse et recommendations :
- Comparatif des modèles et recommendations

* En plus de ce code un support visuel a été réalisé qui ne figuera pas ici.
