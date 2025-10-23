# 📈 Projet Time Series : De ARIMA au Deep Learning

## 📌 Aperçu du Projet
Ce projet explore différentes méthodes de prédiction de séries temporelles, en comparant les performances des modèles classiques (ARIMA) avec des approches de Deep Learning (ANN, RNN, LSTM, Transformers). Deux études de cas sont présentées :
- **Projet 1** : Prédiction du prix du Bitcoin
- **Projet 2** : Classification de sentiments (NLP)

---

## 🧠 Méthodologie

### 🔹 Projet 1 : Prédiction du Prix du Bitcoin
- **Objectif** : Prédire le prix de clôture du Bitcoin
- **Modèles utilisés** :
  - ARIMA
  - Moyenne Mobile (baseline)
  - RNN & LSTM
- **Étapes clés** :
  - Nettoyage et normalisation des données
  - Décomposition saisonnière
  - Recherche de grille pour ARIMA
  - Entraînement et évaluation des modèles

### 🔹 Projet 2 : Analyse de Sentiments
- **Objectif** : Classer les avis en positifs ou négatifs
- **Modèles utilisés** :
  - LSTM (plusieurs architectures)
  - Transformer
- **Étapes clés** :
  - Nettoyage de texte (stopwords, lemmatisation, tokenisation)
  - Vectorisation des textes
  - Entraînement avec EarlyStopping et ReduceLROnPlateau
  - Évaluation via accuracy, recall, F1-score

---

## 📊 Résultats Clés

### Projet 1
- **ARIMA** : Performances limitées sur données volatiles
- **Moyenne Mobile** : Meilleure performance que ARIMA et Baseline
- **LSTM** : Capture mieux les dépendances longues que RNN

### Projet 2
- **Meilleur modèle** : LSTM avec Global Average Pooling
- **Transformer** : Accuracy de 88%, bon équilibre précision/rappel

---

## 🛠️ Technologies Utilisées
- `Python`
- `Pandas`, `NumPy`
- `Statsmodels` (ARIMA)
- `TensorFlow/Keras` (RNN, LSTM, Transformer)
- `Scikit-learn` (métriques)
- `Matplotlib`, `Seaborn` (visualisation)

---

## 👥 Auteurs
- Fatima-Ezzahra Iddouch

---

> 📁 *Les notebooks, datasets et scripts sont disponibles dans ce dépôt.*
