# ❤️ Heart Disease Prediction – Machine Learning Classification

## 📌 Présentation du projet

Ce projet consiste à développer un modèle de Machine Learning capable de prédire la présence d'une maladie cardiovasculaire à partir de données médicales de patients.

L’objectif est d’explorer, nettoyer et préparer les données avant d’entraîner un modèle de classification permettant d’aider à l’identification précoce des risques cardiaques.

---

## 🎯 Objectifs

* Analyser les facteurs associés aux maladies cardiovasculaires
* Nettoyer et préparer les données médicales
* Détecter les valeurs manquantes et incohérences
* Construire un pipeline de Machine Learning
* Prédire la présence d'une pathologie cardiaque
* Évaluer les performances du modèle de classification
* Analyser l’équité des prédictions selon le sexe des patients

---

## 📊 Dataset utilisé

Le projet utilise le dataset **Heart Disease UCI**.

Le dataset contient des informations médicales telles que :

* Âge
* Sexe
* Type de douleur thoracique
* Tension artérielle au repos
* Cholestérol sanguin
* Glycémie à jeun
* Résultats ECG
* Fréquence cardiaque maximale
* Angine induite par l’effort
* Dépression ST (Oldpeak)
* Nombre de vaisseaux majeurs
* Thalassemia

Variable cible :

```python
num
```

Représentant le niveau de maladie cardiaque.

---

## 🛠️ Étapes du projet

### 1. Exploration des données

Analyse de :

* La distribution des patients
* Les différentes catégories de maladies
* Les statistiques descriptives
* Les corrélations entre variables

---

### 2. Nettoyage des données

Traitements réalisés :

* Suppression des colonnes inutiles
* Détection des données insignifiantes
* Analyse des valeurs manquantes
* Contrôle de la qualité des données
* Préparation des variables pour le Machine Learning

---

### 3. Analyse exploratoire (EDA)

Visualisations réalisées :

* Distribution des patients selon les niveaux de maladie
* Analyse des variables médicales
* Étude des facteurs de risque
* Comparaison des groupes de patients

---

### 4. Préparation des données

* Séparation des variables explicatives et de la variable cible
* Encodage des variables catégorielles
* Standardisation des données
* Séparation entraînement / test

Répartition :

```python
90 % entraînement
10 % test
```

---

## 🤖 Modèles de Machine Learning

Plusieurs approches de classification ont été étudiées :

* Support Vector Machine (SVM)
* Régression Logistique
* Arbres de Décision
* Random Forest
* Méthodes de classification supervisée

Le notebook met principalement en œuvre un modèle :

```python
sklearn.svm.SVC()
```

---

## 📈 Évaluation des performances

Les performances du modèle sont évaluées à l’aide de :

* Accuracy Score
* Classification Report
* Matrice de confusion
* Comparaison des prédictions réelles et prédites

```python
classification_report()
confusion_matrix()
accuracy_score()
```

---

## ⚖️ Analyse d’équité du modèle

Une analyse complémentaire a été réalisée afin d’évaluer les performances du modèle selon le sexe des patients.

Comparaison de :

* Précision sur les hommes
* Précision sur les femmes

Objectif :

* Détecter d’éventuels biais algorithmiques
* Vérifier l’équité du modèle de classification

---

## 📌 Résultats

Le modèle est capable d’identifier efficacement les patients présentant un risque de maladie cardiaque à partir de données cliniques.

L’analyse montre que certaines variables médicales jouent un rôle majeur dans la prédiction :

* Âge
* Douleur thoracique
* Cholestérol
* Fréquence cardiaque maximale
* Oldpeak
* Résultats ECG

---

## 🧰 Technologies utilisées

* Python
* Pandas
* NumPy
* Scikit-Learn
* SciPy
* Seaborn
* Matplotlib
* Jupyter Notebook

---

## 📁 Structure du projet

```bash
heart-disease-prediction-ml/
│
├── Prediction.ipynb
├── HeartDiseaseUCI.csv
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

### Cloner le projet

```bash
git clone https://github.com/Obounou/heart-disease-prediction-ml.git
cd heart-disease-prediction-ml
```

### Installer les dépendances

```bash
pip install -r requirements.txt
```

### Lancer le notebook

```bash
jupyter notebook SEANCE3.ipynb
```

---

## 📦 Requirements

```txt
pandas
numpy
scipy
scikit-learn
matplotlib
seaborn
jupyter
```

---

## ✅ Compétences démontrées

* Analyse exploratoire de données
* Préparation de données médicales
* Classification supervisée
* Machine Learning
* Support Vector Machine (SVM)
* Évaluation de modèles
* Matrice de confusion
* Classification Report
* Analyse de biais algorithmiques
* Visualisation de données

---

## 🚀 Améliorations possibles

* Optimisation des hyperparamètres
* Comparaison avec XGBoost et Random Forest
* Déploiement via Streamlit
* API Flask pour la prédiction en temps réel
* Tableau de bord Power BI pour le suivi des résultats

---

## 👤 Auteur

**Obounou Zolo Elvis**
Étudiant en Intelligence Artificielle & Data Science – Aivancity Paris-Cachan
