# Détection d'Objets sur Vidéo avec YOLOv8 
Détection d’objets en temps réel sur une vidéo avec YOLOv8 dans Google Colab

## Description
Ce projet implémente une solution complète de détection d'objets à partir d'une vidéo en utilisant le modèle YOLOv8 (Ultralytics) dans un environnement Google Colab. Il permet d'analyser une vidéo image par image, d'appliquer une détection d'objets, d'annoter les images avec des bounding boxes, puis de reconstituer une vidéo de sortie.

## Objectifs
Charger une vidéo depuis l'ordinateur de l'utilisateur.

Appliquer la détection d’objets sur chaque frame avec YOLOv8.

Générer une vidéo annotée contenant les objets détectés.

Afficher ou télécharger la vidéo traitée dans Google Colab.

## Technologies utilisées
Python

Google Colab

OpenCV

Ultralytics (YOLOv8)

HTML (pour affichage vidéo dans le notebook)

## Fonctionnalités
Upload manuel de vidéos .mp4

Traitement vidéo avec YOLOv8 (yolov8n.pt ou tout autre modèle personnalisé)

Sauvegarde automatique de la vidéo traitée (output.mp4)

Visualisation dans le notebook via HTML

Téléchargement local de la vidéo générée

## Installation et utilisation
Ouvrir le notebook Google Colab ([https://colab.research.google.com/drive/1JkZUBrdLlhIuaIeEmb1diLuD9FPkHmHg?usp=sharing]).

Suivre les instructions :

1. Installer les dépendances

2. Uploader une vidéo locale

3. Lancer la détection avec YOLOv8

4. Afficher ou télécharger la vidéo traitée
