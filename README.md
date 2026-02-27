# OCR Tifinagh + Correction Automatique NLP

**Étudiante** : Fatima-Zahra Boulaghla  
**Module** : NLP — Master IA Embarquée  

## Description
Système de reconnaissance de caractères Tifinagh (OCR) basé sur un CNN,
couplé à un module de correction automatique par distance de Levenshtein.


## Installation
```bash
pip install -r requirements.txt
```

## Utilisation — Exécuter dans l'ordre
```bash
# 1. Exploration des données
jupyter notebook notebooks/01_exploration.ipynb

# 2. Prétraitement
jupyter notebook notebooks/02_preprocessing.ipynb

# 3. Entraînement CNN
jupyter notebook notebooks/03_model_cnn.ipynb

# 4. Correction NLP
jupyter notebook notebooks/04_correction_nlp.ipynb
```

## Structure du projet
```
tifinagh-ocr-nlp/
├── data/               # Datasets AMHCD64
├── notebooks/          # Notebooks Jupyter (exécuter dans l'ordre)
├── src/                # Code source modulaire
├── results/
│   ├── figures/        # Courbes, matrices de confusion
│   └── models/         # Modèle CNN sauvegardé (.h5)
└── requirements.txt
```

## Dataset
- **AMHCD64** : 25,740 images, 33 classes
- Source : https://www.kaggle.com/datasets/benaddym/amazigh-handwritten-character-database-amhcd