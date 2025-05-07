
# Détection d'anomalies dans les signaux ECG (Projet MLOps – IUT3 FISA VT)

## 🎯 Objectif du projet

Ce projet vise à construire un pipeline de Machine Learning permettant de détecter automatiquement les anomalies cardiaques dans des signaux ECG issus de la base MIT-BIH Arrhythmia.

---

## 📁 Contenu du projet

- `projet_ecg_colab.ipynb` : notebook principal à exécuter sur Google Colab
- `Projet_ECG_VeilleTechno.docx` : rapport modifiable à remettre
- `features.csv` : données extraites à partir des battements ECG
- `modele_ecg.pkl` : modèle entraîné (Random Forest)

---

## 🔧 Étapes du pipeline

1. **Chargement des données MIT-BIH**
2. **Filtrage du signal et détection des pics R**
3. **Découpage en battements individuels**
4. **Extraction de caractéristiques temporelles**
5. **Étiquetage des battements via les annotations**
6. **Équilibrage des classes (sur-échantillonnage)**
7. **Entraînement et évaluation du modèle**
8. **Affichage des performances (matrice de confusion, rapport)**

---

## 📌 Instructions (exécution Colab)

1. Uploader le fichier `.zip` contenant les enregistrements MIT-BIH
2. Suivre les blocs dans l’ordre dans le notebook
3. Télécharger le fichier `.pkl` (modèle entraîné) à la fin si souhaité

---

## 📊 Résultats obtenus

Le modèle Random Forest a atteint une précision de 100 % sur les données équilibrées (classes N et A).

---

## 📦 Données utilisées

- [MIT-BIH Arrhythmia Database (PhysioNet)](https://physionet.org/content/mitdb/1.0.0/)

---

## 🙋 Auteurs

- Mohammad Waqas SAEED – IUT3 FISA VT – 2025

---

## 📝 Licence

Projet académique – Usage pédagogique uniquement.
