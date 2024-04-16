# Procédures vitales au bon fonctionnement du projet (Français)

Nous supposons que Python est installé sur la machine, tout comme Git, et que vous vous trouvez sur votre interface, prêt à travailler, le dépôt importé.

## L'environnement 

1. Installer "virtualenv" (Dans le terminal) : ```pip install virtualenv```          
2. Activer l'environement (terminal, dans le dossier du projet)
    - Sur windows ```virtualenv venv
    .\venv\Scripts\activate```
    - Sur MacOs et Linux ```virtualenv venv
    source venv/bin/activate```

### Dépendances

Lors du projets, plusieurs librairies et bibliothèques ont été utilisées. Pour les sauvegarder, il est nécéssaire de faire ```pip freeze > requirements.txt```. Un fichier sera créé, du nom de "requirements.txt", à la racine. Il contiendra toute les dépendances utiles. 

Pour l'activer, il faut faire ```pip install -r requirements.txt```

## Commentaire et documentation

Tout le code, sans exception, doit être commenté en respecter au mieux les normes.

## Git & GitHub

1. Sélectionner un fichier : ```git add [Nom fichier]```
2. Création du commentaire : ```git commit -m "FR/ commentaire en Français. EN/ English comment."```
3. Envoyer sur GitHub : ```git push```


# Procedures vital to the proper functioning of the project (English)

We assume that Python is installed on the machine, as is Git, and that you are on your interface, ready to work, with the repository imported.

## The environment

1. Install "virtualenv" (In the terminal): ```pip install virtualenv```
2. Activate the environment (terminal, in the project folder)
    - On windows ```virtualenv venv
    .\venv\Scripts\activate```
    - On MacOs and Linux ```virtualenv venv
    source venv/bin/activate```

### Dependencies

During the project, several bookstores and libraries were used. To save them, it is necessary to do ```pip freeze > requirements.txt```. A file will be created, named "requirements.txt", at the root. It will contain all the useful dependencies.

To activate it, you must do ```pip install -r requirements.txt```

## Commentary and documentation

All code, without exception, must be commented on to respect the standards as best as possible.

## Git & GitHub

1. Select a file: ```git add [File name]```
2. Creation of the comment: ```git commit -m "FR/ commentaire en Français. EN/ English comment."```
3. Send to GitHub: ```git push```