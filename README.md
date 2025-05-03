Analyse du dataset Facebook100

Ce dépôt contient un notebook Jupyter (fbProject.ipynb) dédié à l’analyse exploratoire et à l’étude du réseau social Facebook tel qu’il existait en 2005, à travers le dataset Facebook100.
Contexte et objectif

Facebook, lancé le 4 février 2004 à Harvard sous le nom "thefacebook.com", était initialement un réseau social réservé aux étudiants de certaines universités américaines. En septembre 2005, Facebook s’était étendu à plus de 800 collèges et universités, comptant environ 6 millions d’utilisateurs, bien que d’autres réseaux sociaux comme MySpace et Friendster dominaient encore le paysage

.

Le dataset Facebook100 est une capture instantanée anonymisée des connexions d’amitié entre plus de 1,2 million d’utilisateurs affiliés aux 100 premiers collèges ayant rejoint Facebook, avec près de 94 millions de liens d’amitié non pondérés et non orientés

. Chaque utilisateur est caractérisé par des attributs sociaux tels que le statut (étudiant, alumni, personnel, etc.), le dortoir, la majeure, le genre et l’année de diplôme.

L’objectif principal de ce notebook est d’explorer la structure sociale de ces réseaux universitaires, d’analyser les variables démographiques et sociales associées, et de mieux comprendre la dynamique d’adoption et de formation des liens sur Facebook à cette époque.
Contenu du notebook

    Présentation et nettoyage des données du dataset Facebook100

    Analyse descriptive des attributs sociaux (statut, genre, majeure, dortoir, année de diplôme)

    Étude des réseaux d’amitié : densité, distribution des liens, caractéristiques par université

    Visualisations des réseaux et des distributions des variables

    Analyse de l’adoption de Facebook par rapport à la taille des universités

    Discussion sur les biais et limites des données (valeurs manquantes, comptes multiples, etc.)

Prérequis

Pour exécuter ce notebook, il est recommandé d’avoir :

    Python 3.x

    Jupyter Notebook ou JupyterLab

    Bibliothèques Python : pandas, numpy, matplotlib, seaborn, networkx (pour l’analyse réseau), scikit-learn (si modélisation)
