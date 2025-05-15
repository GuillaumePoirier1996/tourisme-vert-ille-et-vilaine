# 🏞️ Analyse du Tourisme Responsable en Ille-et-Vilaine

Ce projet vise à explorer, vectoriser, et regrouper les propositions citoyennes autour du **tourisme durable** en Ille-et-Vilaine à travers des techniques de **traitement naturel du langage naturel (NLP)**.

## 🧠 Étapes du projet

### 1. Nettoyage et Prétraitement (`notebooks/01-preprocessing-nlp.ipynb`)
- Suppression du bruit, lemmatisation, tokenisation.
- Retrait (ou non) des stop-words selon les besoins.

### 2. Vectorisation des mots et phrases (`notebooks/02`, `03`)
- Modèles Word2Vec : CBOW et Skip-Gram.
- Moyennage pour obtenir des embeddings de phrases.

### 3. Visualisation (`notebooks/02-visualisations-et-vectorisation.ipynb`)
- WordCloud personnalisé.
- Représentation 2D des mots/phrases avec **t-SNE**.

### 4. Clustering (`notebooks/04`, `05`)
- K-means et CAH sur les embeddings de phrases.
- Étiquetage automatique des clusters.

### 5. Interface interactive (`dash_app/` à venir)
- Application web Dash avec :
  - WordCloud
  - Sélection des modèles Word2Vec
  - Visualisation interactive
  - Clustering et thématiques

## 🔍 Objectifs

- Identifier les **grands axes d’opinion citoyenne**.
- Mettre en avant des tendances via la vectorisation sémantique.
- Proposer une **interface interactive** pour l'exploration thématique.

## 🛠️ Installation

1. Cloner le dépôt :
```bash
git clone git@github.com:GuillaumePoirier1996/tourisme-vert-ille-et-vilaine.git
cd tourisme-vert-ille-et-vilaine
```

2. Créer un environnement :
```bash
conda env create -f environment.yml
conda activate tourisme_nlp
```

3. Lancer les notebooks ou l'application Dash (à venir).

## 📊 Exemples de sorties
- WordCloud des termes les plus fréquents.
- Représentation 2D des mots et phrases.
- Clusters thématiques : mobilités, gestion des déchets, etc.

<p align="center"> <img src="./outputs/Le tourisme vert en Ille-et-Vilaine.png" width="60%" alt="WordCloud"> </p>

## 📄 Licence
Ce projet est sous licence MIT.

## Contact :
Guillaume Poirier
guillaume.poirier1996@gmail.com
0785548643