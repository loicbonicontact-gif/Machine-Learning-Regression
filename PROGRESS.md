# Suivi du projet — Machine Learning & Régression

## Contexte
Formation Simplon. Brief : NexaData Consulting.
- Cas 1 (individuel) : HabitatPlus — régression sur California Housing (LinearRegression, KNN, DecisionTree, RandomForest ; métriques MAE/MSE/R2).
- Cas 2 (binôme) : Aegis Health Coverage — tarification assurance santé (`data/insurance-data.csv`) avec dashboard Streamlit.

## Fait
- 2026-09-18 : dépôt du repo de la prof cloné en local pour référence.
- 2026-09-18 : dépôt GitHub perso créé et lié : https://github.com/loicbonicontact-gif/Machine-Learning-Regression (public), premier commit poussé (data, notebooks, assets).

- 2026-09-21 : synchronisation avec le repo de la prof (remote `prof`) : aucune nouveauté, contenu identique à la copie initiale.

- 2026-09-24 : `nb_03` terminé par Claude à la demande explicite de l'utilisateur : cellules
  vides remplies (valeurs manquantes, encodage, coefficients, voisins KNN, arbre, importances,
  SVR, MSE/MAE/R², tableau récapitulatif), notebook exécuté sans erreur, réponses aux
  questions rédigées en markdown. Résultats : Random Forest meilleur (R² 0,80, MAE 0,33).

- 2026-09-24 : notebook binôme `Dav , Suz , Lo/aegis-health-coverage suz loic david.ipynb` corrigé :
  chemin du CSV relatif (`../data/insurance-data.csv`), cellule de sauvegarde Windows supprimée,
  cellules vides/en double retirées. Exécuté sur Mac sans erreur (RF optimisé R² 0,877, MAE 2488 $).
- 2026-09-24 : section **Lot 1 : Tabagisme (Loïc)** dans ce notebook, alignée sur la fiche du binôme :
  question principale « le tabagisme est-il le facteur n°1, et de combien ? » + 3 sous-questions
  (sous-groupe dans la distribution, écart chiffré, hommes vs femmes). Résultats : corrélation 0,79
  (vs âge 0,30), +23 616 $ par fumeur (x3,8), 94 % des assurés > 30 000 $ sont fumeurs,
  surcoût +21 917 $ femmes / +24 955 $ hommes.

## Décisions prises
- 2026-09-24 : la décision du 2026-09-18 (Claude n'écrit pas nb_03) est remplacée : l'utilisateur
  a demandé à Claude de finir tout `nb_03` en autonomie.
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

- 2026-09-24 : répartition en lots dans le binôme ; Loïc = Lot 1 Tabagisme, fait dans le notebook
  (pas dans Streamlit) à sa demande. Convention du binôme : chaque lot est ajouté à la fin du
  notebook, après le prétraitement et les modèles.

## Reste à faire
- Supprimer les 2 fichiers parasites `Dav , Suz , Lo/C:\\Users\\...pkl` (créés en exécutant l'ancienne cellule Windows sur Mac).
- Prévenir les coéquipiers des changements du notebook (chemin relatif, cellules retirées).
- Renommer le notebook en `insurance_health_prediction.ipynb` (nom demandé par le brief) — à décider en binôme.
- Relire/comprendre `nb_03` (terminé le 2026-09-24) avant de le rendre.
- Construire le notebook 2 (Aegis Health Coverage / insurance-data.csv) — binôme.
- Construire le Dashboard Streamlit (simulateur de prime) — binôme.
- Préparer le support de présentation (PPTX/PDF, 8-10 slides) — binôme.
