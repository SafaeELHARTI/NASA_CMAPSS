# ✈️ Fleet Engine Monitoring Dashboard
> Mini-projet Data Engineer — Monitoring de fiabilité de moteurs d'avion

## 📌 Contexte

Simulation du rôle d'un data engineer chez un opérateur aérien.
Objectif : monitorer la fiabilité de la flotte de moteurs via un
dashboard Power BI basé sur des données réelles NASA.

## 🎯 Objectif

Construire un pipeline de données complet :
- Extraction et transformation des données capteurs (Python)
- Calcul du RUL (Remaining Useful Life) par moteur
- Visualisation interactive dans Power BI

## 📊 Dataset

- **Source** : NASA CMAPSS N-CMAPSS_DS01
- **Données** : 6 moteurs, 14 capteurs physiques, cycles complets jusqu'à la panne
- **Lien** : [Kaggle - NASA CMAPSS](https://www.kaggle.com/datasets/bishals098/nasa-cmapss-2-engine-degradation)

> ⚠️ Les fichiers `.pbix` et `.csv` ne sont pas inclus dans ce repo car ils dépassent
> la limite GitHub (100 MB). Pour les générer, exécute le notebook `data_preparation.ipynb`
> depuis Kaggle Notebooks — aucun téléchargement local requis.

## 🛠️ Stack technique

| Outil | Usage |
|-------|-------|
| Python (pandas, h5py) | Extraction et transformation des données |
| Kaggle Notebooks | Environnement cloud (sans téléchargement local) |
| Power BI Desktop | Visualisation et dashboard interactif |
| GitHub | Versioning et partage du projet |

## 📁 Structure du projet
