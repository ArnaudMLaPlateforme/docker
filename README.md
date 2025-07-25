# 🐳 Job 01 - Docker : Mes premiers pas avec Docker

## 🎯 Objectifs du projet

Ce projet est une première introduction à Docker dans le cadre de la formation. Il a pour but de :

- Comprendre les bases de Docker
- Apprendre à installer, exécuter et interagir avec des **images** et **containers Docker**
- Découvrir l’image officielle [`welcome-to-docker`](https://github.com/docker/welcome-to-docker)

---

## ✅ Étapes réalisées

### 1. Installation de Docker
![Capture d'écran de la version Docker](images/install-docker-01.png)

- Docker Desktop a été installé avec succès sur mon ordinateur.

### 2. Création et connexion au compte Docker
- ![Capture d'écran de la version Docker](images/launch-docker.png)

### 3. Vérification de la version d'installation de docker avec la commande
docker --version
- ![Capture d'écran de la version Docker](images/docker-version.png)

### 4. Test des commandes de base dans le terminal :
👉 docker info : affichage des informations système Docker avec docker info
- ![Capture d'écran de la version Docker](images/docker-info.png)
- ![Capture d'écran de la version Docker](images/docker-info-2.png)

👉 docker ps : affichage des containers en cours avec docker ps
- ![Capture d'écran de la version Docker](images/docker-ps.png)

👉 docker images : affichage des images Docker disponibles localement avec docker images
- ![Capture d'écran de la version Docker](images/docker-images.png)

👉 docker run : démarrer un container Docker à partir d’une image. Message d’erreur indiquant que la commande docker run nécessite au minimum un argument, qui est le nom de l’image Docker que je veux lancer.
- ![Capture d'écran de la version Docker](images/docker-run.png)

👉 docker stop : arrêter un container en cours d'exécution. Message d’erreur indiquant que la commande docker stop nécessite au minimum un argument, qui est le nom de l’image Docker en cours d'exécution.
- ![Capture d'écran de la version Docker](images/docker-stop.png)

### 5. Récupération de l’image Docker
👉 docker pull docker/welcome-to-docker
- ![Capture d'écran de la version Docker](images/docker-pull.png)

👉 docker images docker/welcome-to-docker : Vérification que l'image welcome-to-docker est bien présente
- ![Capture d'écran de la version Docker](images/docker-images-welcome-to-docker.png)

### 6. Construction du container Docker
👉 docker run -it --rm -p 8080:80 docker/welcome-to-docker :  Lancement du container avec un port valide
- ![Capture d'écran de la version Docker](images/docker-run-welcome-to-docker.png)

👉 http://localhost:8080/ : Lancement de l'application dans le navigateur
- ![Capture d'écran de la version Docker](images/docker-navigator.png)

### 7. Arrêt du container en cours
👉 Ctrl + C : 
- ![Capture d'écran de la version Docker](images/docker-stop-welcome-to-docker.png)

### 8. Suppression de container
👉 Avec l'utilisation de --rm, le container est automatiquement supprimé juste après l'avoir arrêté.
La commande docker ps montre que le container n'existe plus
- ![Capture d'écran de la version Docker](images/docker-delete.png)

### 9. Suppression de l'image du container
👉 docker rmi docker/welcome-to-docker
- ![Capture d'écran de la version Docker](images/docker-rmi.png)


