# Classification d'images MNIST avec un CNN

Ce repository contient un notebook Jupyter, `cnn-mnist.ipynb`, qui guide à travers les étapes suivantes :

1. **Téléchargement et prétraitement des données** : 
    - Chargement du dataset MNIST.
    - Mise à l'échelle des images.
    - Séparation des données en ensembles d'entraînement, de validation et de test.
    
2. **Création du modèle et entraînement** :
    - Construction d'un modèle CNN avec deux couches de convolution.
    - Compilation du modèle avec l'optimiseur Adam.
    - Entraînement du modèle avec arrêt anticipé.
    
3. **Test du modèle** :
    - Évaluation de la perte et de la précision sur l'ensemble de test.
    
4. **Affichage des prédictions** :
    - Visualisation d'une image test et de ses prédictions sous forme de graphique à barres.
