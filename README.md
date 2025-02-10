# NBA Shooting Data Analysis

Projet d'analyse des tirs de Seth Curry durant les Playoffs NBA 2021
Ce projet analyse les performances de tir de Seth Curry pour :
- Évaluer son taux de réussite global
- Mesurer l'impact des défenseurs adverses
- Comprendre quelles zones du terrain maximisent ses chances de marquer

##  Structure
- **data/** : données brutes
- **notebooks/** : EDA, visualisation, analyse
- **src/** : fonctions Python réutilisables
- **reports/** : rapport final et graphiques

## Méthodologie

1. Préparation et nettoyage des données (`01_exploration.ipynb`)
2. Exploration visuelle :
   - Répartition des tirs réussis/ratés
   - Répartition par défenseur
   - Positions des tirs (`X`, `Y`)
3. Analyse :
   - Calcul des taux de réussite globaux
   - Comparaison par défenseur
   - Comparaison par plage de tir
   - Identification des zones les plus rentables
  
## Résultats

Les résultats clés sont exportés :
- `success_by_defender.csv` : taux de réussite par défenseur
- `success_by_defender_range.csv` : taux combiné défenseur + range

Ces résultats sont présentés et commentés dans `reports/final_report.pdf`.

##  Librairies
- Python
- pandas
- matplotlib
- seaborn
- Jupyter

##  Comment lancer
1. Créer un venv : `python -m venv .venv`
2. Activer : `.venv\Scripts\Activate`
3. Installer : `python -m pip install -r requirements.txt`
4. Lancer VS Code : `code .`


Auteur: Guefif Jouneid