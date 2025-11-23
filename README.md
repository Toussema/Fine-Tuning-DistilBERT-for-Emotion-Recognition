# Fine-Tuning DistilBERT pour la Classification des Émotions

Ce projet montre comment fine-tuner le modèle **DistilBERT** sur le dataset **dair-ai/emotion** afin de classifier des textes selon 6 émotions :  
**anger, fear, joy, love, sadness, surprise**.

Le projet est entièrement développé sur **Google Colab** avec GPU, en utilisant les bibliothèques HuggingFace (`transformers`, `datasets`) et PyTorch.

---

## 📌 Objectifs
- Charger et explorer un dataset NLP
- Tokenizer les textes avec DistilBERT
- Encoder les données et préparer les tenseurs
- Entraîner un modèle Transformer avec *fine-tuning*
- Évaluer les performances (Accuracy, F1-score)
- Tester le modèle sur des phrases personnalisées

---
