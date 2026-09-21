# Contexte projet — Machine Learning & Régression

## Qui est l'utilisateur
- Débutant, ne relit pas le code lui-même : toujours vérifier son propre travail
  par des tests avant de le présenter.
- Veut apprendre : terminer chaque tâche par un court résumé pédagogique en
  français (quoi, pourquoi), sans jargon non expliqué.
- Langue : explications/résumés en français, code/commentaires/commits en anglais.
- Un seul chantier à la fois. Poser une question fermée (options + recommandation)
  pour toute décision non couverte par ce document.

## Le projet
Formation Data Analyst (Simplon). Brief fourni par la prof (Salma AZIZ),
repo original : https://github.com/Salma-AZIZ/Machine-Learning-Mise-en-pratique

Client fictif : NexaData Consulting, deux volets :

1. **HabitatPlus (individuel)** — notebook de cadrage sur la régression :
   comparer 4 algorithmes (LinearRegression, KNN, DecisionTree, RandomForest)
   + métriques (MAE, MSE, R²) sur le dataset **California Housing**
   (chargé via `sklearn.datasets.fetch_california_housing`, pas un fichier local).
   - Fichier : `notebooks/nb_03_Apprentissage_Supervisé_Regression.ipynb`
   - État : template à trous, toutes les cellules de code sont vides
     (commentaires `# Insérez votre code ici...`). Rien n'est encore fait.

2. **Aegis Health Coverage (en binôme)** — projet réel de tarification
   d'assurance santé à partir de `data/insurance-data.csv`
   (colonnes : age, sex, bmi, children, smoker, region, expenses — cible = expenses).
   Attendus :
   - Prétraitement sans fuite de données (encodage catégoriel, scaling).
   - Entraîner/comparer plusieurs modèles de régression, optimiser le meilleur.
   - Dashboard Streamlit : analyse visuelle des coûts + simulateur interactif
     de prime en temps réel.

## Livrables attendus (brief)
1. Notebook individuel exécuté et commenté (California Housing).
2. Dépôt GitHub du projet en binôme : notebook 2 (`insurance_health_prediction.ipynb`)
   + code Streamlit (`app.py` et fichiers associés).
3. Support de présentation (PPTX/PDF, 8-10 slides) avec captures du dashboard.

## Ressources fournies
- PEP 8 : https://peps.python.org/pep-0008/
- Scikit-learn supervised learning : https://scikit-learn.org/stable/supervised_learning.html
- Documentation Streamlit : https://docs.streamlit.io/

## État du dépôt
- Dépôt GitHub dédié créé et poussé : https://github.com/loicbonicontact-gif/Machine-Learning-Regression (public)
- Contenu actuel : `README.md`, `assets/`, `data/`, `notebooks/` (repris du repo
  de la prof).
- Pas encore de dossier `dashboard/` (Streamlit) ni de notebook 2 (Aegis) —
  à créer.
- Un projet séparé existe pour la Classification :
  https://github.com/loicbonicontact-gif/Machine-Learning-Classification
  (renommé depuis `Machine-Learning-Mise-en-pratique`). Ne pas mélanger les deux.

## Reste à faire (voir aussi PROGRESS.md)
- Compléter le notebook 1 (California Housing).
- Créer le notebook 2 (Aegis Health Coverage / insurance-data.csv).
- Construire le Dashboard Streamlit (simulateur de prime).
- Préparer le support de présentation.

## Rituel de session
- Lire `PROGRESS.md` en début de session et résumer en 3 lignes où on en est.
- Mettre `PROGRESS.md` à jour en fin de session (fait / reste / décisions prises).
