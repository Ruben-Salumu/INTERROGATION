# INTERROGATION
Ce dépôt contient deux notebooks Jupyter pour des tâches d'apprentissage automatique utilisant des ensembles de données du UCI Machine Learning Repository. Les notebooks implémentent des flux de travail pour la régression et la classification, incluant l'analyse des données, le prétraitement, l'entraînement des modèles, l'évaluation et la visualisation.

# Notebooks

1. classification.ipynb
Jeu de données : Iris
Tâche : Classer les espèces d'iris (classification multi-classe).
Modèles : Réseau de neurones peu profond (2 couches cachées), Random Forest Classifier, SVC (2 variantes), K-Neighbors Classifier, et Decision Tree Classifier.
Métriques : Précision, précision pondérée, rappel pondéré et score F1 pondéré.
Sorties : Graphique de la distribution des classes et graphique de la précision d'entraînement/validation, enregistrés dans le dossier INTERROGATION.

2. regression.ipynb
Jeu de données : Wine Quality (vin blanc)
Tâche : Prédire la qualité du vin (variable continue) par régression.
Modèles : Réseau de neurones peu profond (2 couches cachées), Régression Linéaire, Random Forest Regressor (2 variantes), et SVR (2 variantes).
Métriques : Erreur quadratique moyenne (MSE) et score R².
Sorties : Histogramme de la distribution de la qualité du vin et graphique de la perte d'entraînement/validation

# Configuration
Placez les jeux de données (winequality-white.csv et iris.data) dans le dossier INTERROGATION.
Bibliothèques requises : numpy, pandas, matplotlib, seaborn, scikit-learn, tensorflow.
Exécutez les notebooks pour générer les graphiques et les métriques.
# Jeux de données
Wine Quality : https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-white.csv
Iris : https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data
