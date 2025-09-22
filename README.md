# 📱 Image Captioning App for the Visually Impaired

## 🎯 Objectif du projet
Développer une application mobile qui génère automatiquement des légendes pour les images afin d’améliorer l’accessibilité des personnes non-voyantes.  
L’application capture une image via la caméra du smartphone et produit une **description audio** en langage naturel.

---

## 🧠 Méthodologie
- **CNN (VGG16, DenseNet201)** : extraction des caractéristiques visuelles.  
- **RNN & LSTM** : génération des légendes textuelles.  
- **Transfer Learning** : réutilisation de modèles pré-entraînés pour améliorer la précision.  
- **Dataset** : Flickr8k (images + légendes).  
- **Évaluation** : BLEU Score pour mesurer la qualité des descriptions.  

---

## 🛠️ Outils & Technologies
- **Langage** : Python  
- **Frameworks** : PyTorch, TensorFlow, Keras  
- **Librairies** : NumPy, Pandas, Matplotlib, Seaborn, Pickle, Tqdm  
- **Environnements** : Jupyter Notebook, Google Colab  
- **Déploiement mobile** : Android Studio + TensorFlow Lite  

---

## 📊 Résultats
- Comparaison entre VGG16 et DenseNet201.  
- VGG16 : bonne précision mais plus lourd à entraîner.  
- DenseNet201 : meilleur compromis entre précision et rapidité.  
- BLEU Score utilisé pour valider les performances.  

---

## 🚀 Perspectives
- Améliorer les performances avec des modèles plus récents (Transformers/ViT).  
- Étendre le dataset pour une meilleure généralisation.  
- Intégrer un module de synthèse vocale multilingue pour rendre l’application plus inclusive.  

---

## 🎥 Démonstration du projet
[▶️ Cliquez ici pour voir la vidéo](video.mp4)




