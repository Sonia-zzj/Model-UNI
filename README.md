# Model-UNI
### Introduction
Nous avons validé la performance de l'ensemble de le modèle UNI dans l'ensemble données de TCGA.


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
### Références
