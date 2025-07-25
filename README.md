# 🐳 Job 01 - Docker : Mes premiers pas avec Docker

## 🎯 Objectifs du projet

Ce projet est une première introduction à Docker dans le cadre de la formation. Il a pour but de :

- Comprendre les bases de Docker
- Apprendre à installer, exécuter et interagir avec des **images** et **conteneurs Docker**
- Découvrir l’image officielle [`welcome-to-docker`](https://github.com/docker/welcome-to-docker)

---

## ✅ Étapes réalisées

### 1. Installation de Docker
![Capture d'écran de la version Docker](images/install-docker-01.png)

- Docker Desktop a été installé avec succès sur mon ordinateur.

### 2. Création et connexion au compte Docker
- ![Capture d'écran de la version Docker](images/launch-docker.png)

### 3. Vérifier la version d'installation de docker avec la commande
docker --version
- ![Capture d'écran de la version Docker](images/docker-version.png)

### 4. Tester les commandes de base dans le terminal :
👉 docker info : affichage des informations système Docker avec docker info
- ![Capture d'écran de la version Docker](images/docker-info.png)
- ![Capture d'écran de la version Docker](images/docker-info-2.png)

👉 docker ps : affichage des conteneurs en cours avec docker ps
- ![Capture d'écran de la version Docker](images/docker-ps.png)

👉 docker images : affichage des images Docker disponibles localement avec docker images
- ![Capture d'écran de la version Docker](images/docker-images.png)

👉 docker run : démarrer un conteneur Docker à partir d’une image. Message d’erreur indiquant que la commande docker run nécessite au minimum un argument, qui est le nom de l’image Docker que je veux lancer.
- ![Capture d'écran de la version Docker](images/docker-run.png)

👉 docker stop : arrêter un conteneur en cours d'exécution. Message d’erreur indiquant que la commande docker stop nécessite au minimum un argument, qui est le nom de l’image Docker en cours d'exécution.
- ![Capture d'écran de la version Docker](images/docker-stop.png)

### 5. Récupérer l’image Docker
👉 docker pull docker/welcome-to-docker
- ![Capture d'écran de la version Docker](images/docker-pull.png)

👉 docker images docker/welcome-to-docker
- ![Capture d'écran de la version Docker](images/docker-images-welcome-to-docker.png)
