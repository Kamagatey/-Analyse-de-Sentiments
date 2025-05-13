# 📰 Analyse de Sentiments des Articles Économiques du Monde

Ce projet vise à analyser les **sentiments** exprimés dans les articles économiques du journal **Le Monde**, en utilisant des techniques modernes de **traitement du langage naturel (NLP)**.

---

## 📁 Contenu du projet

Le notebook comprend les étapes suivantes :

1. 📥 Collecte et nettoyage des données  
2. 🧹 Prétraitement des textes :  
   - Nettoyage avec regex  
   - Tokenisation  
   - Suppression des stop words  
   - Lemmatisation  
3. 📊 Analyse exploratoire des données  
4. 🤖 Modélisation avec **CatBoost**  
5. 📈 Visualisation des résultats

---

## 📦 Structure des données

Le jeu de données contient des articles du journal **Le Monde**, avec les colonnes suivantes :

- 🧑 Auteur  
- 🌐 URL  
- 📝 Titre  
- 📄 Texte (brut et original)  
- 📍 Localisation  
- 🧍 Personne mentionnée  
- 🏢 Entreprise  
- 😊 Sentiment (`Positive` / `Negative`)  
- ⚙️ Autres métadonnées

---

## 🧠 Méthodologie

Techniques de NLP et modélisation utilisées :

- Nettoyage de texte via **Regex**
- Tokenisation avec **NLTK**
- Suppression des **stop words**
- Lemmatisation avec **spaCy**
- Vectorisation **TF-IDF**
- Modélisation avec **CatBoostClassifier**
- Visualisation : **matplotlib**, **seaborn**

---

## ✅ Résultats

Le modèle permet de :
- Classer les sentiments des articles avec une bonne précision
- Identifier les mots dominants dans les textes à travers :
  - Nuages de mots
  - Graphiques de fréquence
- Offrir des **insights thématiques** sur le contenu économique du journal

---

## ⚙️ Exécution

1. 📦 Installer les dépendances :

```bash
pip install pandas nltk spacy matplotlib seaborn catboost
python -m spacy download fr_core_news_sm
```


2. ▶️ Lancer le notebook :

jupyter notebook projet_NLP(1).ipynb

## 👨‍💻 Auteurs

- KAMAGATE Youssouf

- SORO DOBA

📧 kamagatey25@gmail.com
📞 +225 07 79 98 67 99
