
# 📦 EfficientNet Image Classification

Ce projet entraîne un modèle EfficientNetB5 pour classifier des images.
**Lien vers les données** : [Cliquez ici](https://www.kaggle.com/datasets/orvile/brain-cancer-mri-dataset).

## 🔧 Structure des données

Les données doivent être organisées ainsi dans le dossier `data/` :

```
data/
├── class_1/
│   ├── img1.jpg
│   └── ...
├── class_2/
│   ├── img2.jpg
│   └── ...
└── class_3/
    ├── img3.jpg
    └── ...
```

## Lancer le notebook

1. Installez les dépendances :

```
pip install -r requirements.txt
```

2. Lancez le notebook :

```
jupyter notebook classification_efficientnet.ipynb
```

## Fichiers générés

- `data_ml_efficient_net/`: structure train/val/test
- `best_model.h5`: meilleur modèle sauvegardé
- `history_training.csv`: historique d'entraînement (si activé)

## Sorties

- Matrice de confusion
- Courbes de précision/perte
- Rapport de classification détaillé
