# Python for data analysis

Yassin HASSAN
Base de données  Census income
https://archive.ics.uci.edu/ml/datasets/Census+Income

## Contexte de la base de donnée

Pour ce  projet, nous allons utilizer la base de données Census Income disponible sur le repertoire de l’ UCIrvine Machine Learning Repository

Le “US Adult Census” est un jeu de données de 48 842 entrées extraites de la base de donnée  USCensus  datant de 1994.

## Objectif

Notre but est de prédire  si les revenus d’un individu  seront  supérieur à 50 000 dollars par an sur la base de plusieurs  caractéristiques  socioculturelles continues dans le jeu de données.

On cherche à prédire la colonne **income**.

## Analyse descriptive des données

- **age** – âge de l’individu
-- Nombre  entier  supérieur à 0
- **type_employer** – Type d’employeur de l’individu
-- Private, Self-­emp­-not-­inc, Self-­emp-­inc, Federal-­gov, Local-­gov, State-­gov, Without-­pay, Never-­worked.
- **fnlwgt** – final weight, nombre de personnes le census estime que cette observation représente
-- Nombre entire supérieur à 0
- **education** – Plus haut  niveau  d’éducation de l’individu
-- Bachelors, Some­-college, 11th, HS-­grad, Prof-­school, Assoc-­acdm, Assoc-­voc,9th, 7th­8th, 12th, Masters, 1st-­4th, 10th, Doctorate, 5th-­6th, Preschool.
- **education_num** – Plus haut  niveau  d’éducation de l’individu sous forme  numérique
-- Nombre entire supérieur à 0
- **marital** – Etat civil de l’individu
-- Married­-civ­-spouse, Divorced, Never­-married, Separated, Widowed, Married­-spouse­-absent, Married­-AF­-spouse.
- **occupation** – Occupation de l’individu
-- Tech­-support, Craf-t­repair, Other-­service, Sales, Exec­-managerial,Prof-­specialty, Handlers-­cleaners, Machine­-op-­inspct, Adm­-clerical,Farming-­fishing, Transport-­moving, Priv-­house­-serv, Protective­-serv,Armed­-Forces.
- **relationship** – Observations réalisées des relations de l’individu
-- Wife, Own­-child, Husband, Not­-in­-family, Other­-relative, Unmarried
- **race** – description ethnique de l’individu
-- White, Asian­-Pac­-Islander, Amer­-Indian­-Eskimo, Other, Black.
- **sex** – sexe de l’individu
-- Male, Female
- **capital_gain** – gains de capitaux  enregistrés
-- Nombre  entier  supérieur  ou  égal à 0
- **capital_loss** – perte de capitaux  enregistrés
-- Nombre  entier  supérieur  ou  égal à 0
- **hr_per_week** – heures de travail par semaine
-- Nombre  entier  supérieur  ou  égal à 0
- **country** – pays d’origine de l’individu
-- United-­States, Cambodia, England, Puerto­Rico, Canada, Germany,Outlying­-US(Guam-­USVI-­etc), India, Japan, Greece, South, China, Cuba, Iran,Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal,Ireland, France, Dominican-­Republic, Laos, Ecuador, Taiwan, Haiti, Columbia,Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El­-Salvador,Trinadad&Tobago, Peru, Hong, Holand­-Netherlands
- **income** – valeur  booleen  indiquant  si  l’individu  gagne plus de 50000 dollars par an
-- <=50k, >50k
