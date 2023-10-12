# Projet de Détection de Casque de Chantier et de Veste Fluorescente

Bienvenue dans le projet de détection de casque de chantier et de veste fluorescente ! Cette application Flask utilise la webcam pour détecter la présence de ces éléments de sécurité sur une personne. Vous pouvez rapidement mettre en place et utiliser cette application en suivant les étapes ci-dessous.

## Prérequis

Assurez-vous d'avoir les éléments suivants installés sur votre système avant de commencer :

- Python 3.x
- [Git](https://git-scm.com/)

## Installation

1. Clonez le projet depuis GitHub en utilisant la commande suivante :

   ```bash
   git clone https://github.com/shurens/brief_uniforme_yolo.git
   ```

2. Accédez au répertoire du projet.

3. Installez les bibliothèques requises en utilisant `pip`. Nous vous recommandons d'utiliser un environnement virtuel pour isoler les dépendances du projet(Si vous êtes sous windows, il faudra créer un environnement virtuel sous windows, et non WSL car la webcam ne fontion pas sur WSL).


   Ensuite, installez les bibliothèques depuis le fichier `requirements.txt` :

   ```bash
   pip install -r requirements.txt
   ```

## Utilisation

Une fois le projet et les dépendances installés, vous êtes prêt à lancer l'application Flask :

```bash
python app.py
```

Accédez à l'application dans votre navigateur en ouvrant l'URL suivante : [http://localhost:5000/](http://localhost:5000/)

L'application vous permettra de détecter la présence de casques de chantier et de vestes fluorescentes dans la vidéo en direct de votre webcam.


