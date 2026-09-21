# Suivi du projet — Machine Learning & Régression

## Contexte
Formation Simplon. Brief : NexaData Consulting.
- Cas 1 (individuel) : HabitatPlus — régression sur California Housing (LinearRegression, KNN, DecisionTree, RandomForest ; métriques MAE/MSE/R2).
- Cas 2 (binôme) : Aegis Health Coverage — tarification assurance santé (`data/insurance-data.csv`) avec dashboard Streamlit.

## Fait
- 2026-09-18 : dépôt du repo de la prof cloné en local pour référence.
- 2026-09-18 : dépôt GitHub perso créé et lié : https://github.com/loicbonicontact-gif/Machine-Learning-Regression (public), premier commit poussé (data, notebooks, assets).

## Décisions prises
- Un repo GitHub dédié à ce projet Régression (séparé du repo Classification existant).
- Visibilité : public.
- Confirmé : le dataset California Housing n'existe que dans `nb_03_Apprentissage_Supervisé_Regression.ipynb` (le fichier `nb_01` du repo traite du Titanic, module Prétraitement — nommage différent de "Notebook 1" utilisé dans le brief pour désigner le 1er notebook du module Régression).
- 2026-09-18 : deux tentatives de remplissage de `nb_03` faites par Claude puis annulées
  à la demande — l'Activité 1 du brief est un exercice individuel destiné à
  l'utilisateur lui-même (révision personnelle), pas une tâche à déléguer. Le fichier
  `nb_03` est donc resté dans son état "template à trous" d'origine.
- Rôle convenu sur ce chantier : Claude n'écrit pas le code du notebook 1 à la place
  de l'utilisateur ; il peut expliquer, guider, corriger ou répondre à des questions
  pendant que l'utilisateur code lui-même.

## Reste à faire
- L'utilisateur remplit lui-même `nb_03_Apprentissage_Supervisé_Regression.ipynb`
  (California Housing, cas HabitatPlus) : EDA, split 80/20, entraînement/comparaison
  de 4 algorithmes (LinearRegression, KNN, DecisionTree, RandomForest), métriques
  MAE/MSE/R², analyse des résidus et importance des variables.
- Construire le notebook 2 (Aegis Health Coverage / insurance-data.csv) — binôme.
- Construire le Dashboard Streamlit (simulateur de prime) — binôme.
- Préparer le support de présentation (PPTX/PDF, 8-10 slides) — binôme.
