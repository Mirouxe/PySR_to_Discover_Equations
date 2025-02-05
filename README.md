# Régression Symbolique avec PySR
Ce projet utilise la régression symbolique pour découvrir des équations à partir de données générées aléatoirement. Il utilise la bibliothèque **PySR** pour effectuer une recherche évolutive sur des ensembles de données d'entrée et de sortie, en essayant de trouver la meilleure équation qui décrit la relation entre ces données. 

La bibliothèque **PySR** a été développé par Miles Cranmer et d'autres collaborateurs. Vous pouvez consulter le projet original sur son dépôt GitHub : [PySR GitHub.](https://github.com/MilesCranmer/PySR)

## Fonctionnalités
- Génération de données d'entrée. L'exemple porte sur une fonction polynomiale simple : $y = x^2 + x^3$
- Entraînement d'un modèle de régression symbolique à l'aide de la bibliothèque PySR.
- Affichage des équations découvertes classées par complexité.
- Récupération et affichage de la meilleure équation trouvée.
- Visualisation des valeurs réelles et des prédictions du modèle sur un graphique.

![image](https://github.com/user-attachments/assets/4fca99f9-4604-4d0d-bd7b-1e8e5c837fc3)

## Prérequis
Avant d'exécuter le code, assurez-vous d'avoir installé les dépendances nécessaires :

- Python 3.6 ou supérieur
- `numpy`
- `matplotlib`
- `pysr`

Vous pouvez installer les dépendances via `pip` :

```bash
pip install numpy matplotlib pysr
