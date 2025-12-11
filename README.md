# MS_A_Applied_stat
https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset


# Prédiction du diabète sur le jeu de données CDC — Aperçu du projet

## Résumé
Construire un pipeline de machine learning pour prédire le statut diabétique en utilisant un jeu de données d'enquête sanitaire du CDC (par exemple, BRFSS / données sur le diabète du CDC). L'objectif est de créer un notebook reproductible qui effectue le nettoyage des données, l'analyse exploratoire, l'entraînement des modèles, l'évaluation et une interprétation de base.

## Objectifs
- Charger et comprendre le jeu de données sur le diabète du CDC.
- Nettoyer et prétraiter les caractéristiques (valeurs manquantes, encodage catégoriel, mise à l'échelle).
- Entraîner des classificateurs de base et avancés pour prédire le diabète.
- Évaluer les modèles avec des métriques appropriées et une validation croisée.
- Fournir une interprétation du modèle et des artefacts prêts pour le déploiement.

## Données (vue d'ensemble)
- Source : Données d'enquête publique du CDC (BRFSS ou similaire) contenant des informations démographiques, sur le mode de vie, des indicateurs cliniques et une étiquette de diabète.
- Colonnes typiques : âge, sexe, IMC, activité physique, tabagisme, pression artérielle, cholestérol, réponses à l'enquête et un indicateur binaire de diabète.
- Problèmes attendus : données manquantes, déséquilibre des classes, types de données mixtes.

## Pipeline / Tâches
1. Ingestion des données et inspection du schéma
2. Nettoyage des données et imputation
3. Analyse exploratoire des données (distributions, corrélations, équilibre des classes)
4. Ingénierie des caractéristiques et encodage
5. Division en ensembles d'entraînement/test et validation croisée
6. Modèle de base (régression logistique) et modèles avancés (Random Forest, XGBoost)
7. Optimisation des hyperparamètres (GridSearch / Validation croisée aléatoire)
8. Évaluation : AUC ROC, précision, rappel, F1, matrice de confusion, calibration
9. Interprétation du modèle (importance des caractéristiques, SHAP)
10. Sauvegarde du meilleur modèle et fourniture d'un code d'inférence d'exemple

## Critères d'évaluation
- Robustesse (performance validée croisée)
- Métriques équilibrées pour les classes déséquilibrées (AUC, rappel pour la classe positive)
- Interprétabilité et reproductibilité

## Livrables
- Notebook Jupyter avec EDA, modélisation et interprétation
- Artefact du modèle entraîné et extrait de code d'inférence
- Court README résumant les résultats et les prochaines étapes

## Prochaines étapes
- Obtenir/confirmer le jeu de données exact du CDC et la définition de la cible.
- Implémenter le prétraitement et le modèle de base.
- Itérer avec la sélection des caractéristiques et l'optimisation en fonction des résultats de validation.



https://www.kaggle.com/code/bharat04/diabetes-detailed-eda-with-conclusion

https://www.kaggle.com/code/abdallahsaadelgendy/diabetes-prediction-eda-preprocessing-models/notebook


https://www.kaggle.com/code/anastasiyaigonina/diabetes-eda-hypothesis-testing-predictions#Feature-engineering


https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset/code?datasetId=1703281&sortBy=voteCount