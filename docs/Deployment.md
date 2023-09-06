# Welcome to Our documentation for Deployment


## Fonctionnalités du Projet
La partie de déploiement de notre projet est une étape cruciale pour réaliser des prédictions sur des objets 3D au format .vtp ou .obj et les visualiser dans notre site web. Cette phase est le pivot central de notre système, permettant aux utilisateurs de tirer pleinement parti de la technologie 3D pour une expérience enrichissante.

Notre objectif principal est d'offrir aux utilisateurs la capacité de télécharger des fichiers 3D, de les soumettre à un processus de prédiction, puis de visualiser les résultats de manière interactive sur notre site web. Pour atteindre cet objectif, nous avons mis en place une architecture en deux parties : le backend et le frontend.

 **La partie backend** : assure le traitement des données, y compris la prédiction à l'aide du modèle MeshSegNet.

 **la partie frontend** :offre une interface conviviale pour les utilisateurs

## Technologies Utilisées

## Configuration et Installation
### 1. Configuration de l'environnement virtuel
Un environnement virtuel est un environnement Python isolé qui permet de gérer les
dépendances spécifiques à un projet sans interférer avec d'autres projets Python sur le
même système. Voici comment créer et configurer un environnement virtuel pour votre
projet:

#### **-Installation de l'outil  `virtualenv`:**

Si vous n'avez pas déjà virtualenv installé sur votre système, vous pouvez l'installer en utilisant pip, qui est l'outil de gestion de paquets Python.
Ouvrez un terminal et exécutez la commande suivante :
` pip install virtualenv `

#### **-Création de l'environnement virtuel:**

Dans le répertoire racine de votre projet, créez
un environnement virtuel en utilisant virtualenv.
Remplacez **nom_env** par le nom que vous
souhaitez donner à votre environnement virtuel : virtualenv nom_env. Cela créera un dossier
avec le nom de votre environnement virtuel contenant une installation Python propre et
isolée

#### **-Activation de l'environnement virtuel:** 
Après avoir créé l'environnement virtuel, vous
devez l'activer. Selon votre système d'exploitation, la commande d'activation varie.<br>
**Sur Windows: `nom_env\Scripts\activate.`**<br>
**Sur macOS ou Linux: `source nom_env/bin/activate`**
### 2. Installation Backend
#### **-Installation de Flask:** 
Dans l'environnement virtuel activé avant, utiliser lacommande suivante pour installer flask: `pip install flask`
#### **-Installation des dépendances Python:**
 Utilisez pip pour installer les packages
Python nécessaires. Dans ce contexte, vous aurez probablement besoin de packages tels
que **Flask**, **NumPy**, **Torch**, **vedo**, **Pandas**, **Spicy**... Exemple: `pip install flask numpy torch`.

Pour lancer le serveur Backend, il faut accéder au dossier de backend, et puis exécuter la
commande `python app.py`
### 3. Installation Frontend
#### **- Installation de Node.js et npm**
 Premièrement, il faut télécharger le fichier Windows
Installer(.msi) ou macOS Installer(.pkg), puis terminer le processus d' installation et la lancer.

Pour lancer le serveur Frontend, il faut accéder au dossier de fronted et exécuter la
commande `npm start`.
## Frontend 

### Structure du Frontend 
### Interface Utilisateur



## Backend 

### Structure du Backend 
### API pour la Prédiction


## Visualisation 3D avec VTK.js