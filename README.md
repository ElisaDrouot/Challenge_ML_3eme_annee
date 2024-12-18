# Challenge de Machine Learning de 3eme année

L'objectif de ce défi consiste à développer une méthode de classification reposant sur des réseaux de neurones pour catégoriser des images provenant de Google Quickdraw (https://quickdraw.withgoogle.com/data). Le jeu de données fourni comprend cinq classes équilibrées, comprenant 15 000 exemples d'entraînement et 5 000 exemples de validation. Ces classes sont constituées de paniers, d'yeux, de lunettes, de lapins et de mains.

## Partie 1

On importe les images nécessaires pour l'entraînement et la validation, puis les on les convertits en matrices de pixels. On normalise les valeurs des pixels de l'image en les divisant par 255. Pour ensuite construire une architecture de modèle séquentielle avec diverses couches. On entraine le modèle puis on essaye d'évaluer la performance du modèle sur les données de test.

## Partie 2

On évalue notre modèle en vérifiant qu'il ai trouvé la bonne catégorie pour 30 images prises au hasard
