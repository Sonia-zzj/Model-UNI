# Model-UNI
### Introduction

À mesure que les données d’imagerie médicale augmentent, nous nous appuyons davantage sur l’IA pour traiter les images pathologiques, ce qui peut nous aider à diagnostiquer les anomalies cellulaires plus précisément et plus rapidement. Le modèle UNI est un modèle formé avec un ensemble de données puissant. L’objectif principal de ce projet est de réaliser les fonctions du modèle UNI et de vérifier sa faisabilité.
J'ai choisi uniquement un petit ensemble de données en fonction de la puissance de traitement de l'ordinateur.

### Protocole 

1. Préparation des données:
    - choisir datasets TCGA
    - dossier images LUSC / dossier image LUAD
2. Prétraitement des données:
    - Redimensionner à une taille standard (en fonction du model ?)
      Certaines des images médicales que j'ai téléchargées sont au format DCM et ces données d'image peuvent être traitées via le format de fichier CSV.
    - Normaliser (en fonction du model ?)
    - diviser en ensemble d'entrainement, de test
3. Implémentation du modele:
    - Téléchargement des poids UNI + Création du modèle
    - ROI Feature Extraction
4. Evaluation du modele:
    - Évaluer les performances du modèle

### Conclusion
Nous avons validé les performances de l'ensemble du modèle UNI sur l'ensemble de données TCGA. L'extraction de caractéristiques sous différentes méthodes d'évaluation a donné de bons résultats, prouvant le rôle puissant du modèle UNI dans la détection des maladies des tissus cellulaires.

### Références
#### [(Paper)] (https://www.nature.com/articles/s41591-024-02857-3)
#### [(Code)] (https://github.com/mahmoodlab/UNI)
