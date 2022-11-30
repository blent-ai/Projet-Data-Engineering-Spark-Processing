<div align="center">
  <a href="https://blent.ai">
    <img src="https://blent-static-media.s3.eu-west-3.amazonaws.com/images/logo/logo_blent_300x.png" alt="Logo Blent.ai" width="200" />
  </a>

  <h2 align="center">Création d'une base d'apprentissage ML à partir de données brutes</h2>

  <p align="center">
    Projet Data Engineering - <a href="https://blent.ai">Blent.ai</a>
    <br />
    <a href="https://blent.ai/app/projects" target="_blank"><strong>Explorer tous les projets »</strong></a>
</div>

<div align="center"><img src="https://cdn.static-media.blent.ai/images/projects/badge_spark_medium.svg" width="120" alt="Badge du projet" /></div>

## À propos du projet

Une entreprise ECommerce collecte de nombreuses informations sur ses utilisateurs lors de leurs visites et de leurs achats sur son site. Afin d'inciter les utilisateurs hésitant à finaliser leur parcours d'achat, elle cherche à proposer des coupons de réduction à ces utilisateurs. Au sein de l'équipe DataLab dont vous faites partie, plusieurs Data Scientists vont travailler sur un algorithme qui vise à construire un modèle prédictif qui va déterminer quels sont les utilisateurs susceptibles de finaliser leur parcours d'achat.

Afin de calibrer cet algorithme prédictif (Machine Learning), les Data Scientists ont besoin d'un historique de plusieurs jours d'événements qui peuvent s'étaler sur plusieurs semaines. En tant que Data Engineer, ton objectif est de construire un programme d'extraction sous forme de job Spark (Spark Scala ou PySpark) que les Data Scientists peuvent exécuter sur un cluster Hadoop lorsqu'ils souhaitent extraire les données brutes et obtenir une base d'apprentissage pour leur algorithme.

> TODO : Compléter cette partie pour apporter plus d'informations sur le contexte du projet.

## Étapes du projet

- [ ] Créer un script Spark sur un échantillon de données
- [ ] Paramétrer le script Spark et écrire la table de sortie vers un système cible
- [ ] Tester le job Spark en conditions réelles
- [ ] Publier le code source et les résultats sur GitHub

La description des étapes est disponible sur la page associée au projet.

> TODO : Cocher les cases au fur et à mesure de l'avancement.

## Structure du projet

Le dépôt Git contient les éléments suivantes.

- `notebooks/` contient les Notebooks Jupyter du projet.
- `src/` contient les codes sources Python principaux du projet, en particulier les codes Spark Scala ou PySpark.
- `data/` contient les données du projet.
- `config/` contient les configurations et paramètres du projet.
- `LICENSE.txt` : licence du projet.
- `requirements.txt` : liste des dépendances Python nécessaires.
- `README.md` : fichier d'accueil.

## Premiers pas

Les instructions suivantes permettent d'exécuter le projet sur son PC.

### Pré-requis

Le projet nécessite Python 3 d'installé sur le système.

> TODO : Ne pas hésiter à compléter/adapter cette partie en fonction des dépendances logicielles.

### Installation

1. Cloner le projet Git.
	```
	git clone https://github.com/blent-ai/Projet-Data-Engineering-Spark-Processing.git
	```
2. Installer les dépendances du fichier `requirements.txt` dans un environnement virtuel.

	**Linux / MacOS**
	```
	python3 -m venv venv/
	source venv/bin/activate
	pip install -r requirements.txt
	```
	**Windows**
	```
	python3 -m venv venv/
	C:\<chemin_dossir>\venv\Scripts\activate.bat
	pip install -r requirements.txt
	```

> TODO :
> - Remplir le fichier `requirements.txt` pour y ajouter les dépendances (Pandas, PySpark, FindSpark, etc).
> - Compléter la procédure d'installation pour l'adapter en fonction des besoins (cluster Dataproc, EMR, etc).

### Démarrage

> TODO : Expliquer en quelques lignes et avec des exemples de ligne de commande comment l'utilisateur peut entraîner ou utiliser lui-même le modèle. 

## Licence

*Ce projet est proposé par <a href="https://blent.ai">Blent.ai</a>. Les données utilisées pour ce projet peuvent être soumises à des droits d'auteur et de propriété intellectuelle. Blent.ai ne peut être responsable des utilisations faites des données utilisées dans le cadre de ce projet.*

> TODO : Ajouter les licences supplémentaires au projet (autres données, outils propriétaires, etc).
