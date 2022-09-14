# Projet de test pour l'apprentissage de Git   

Ceci est un projet de test\
pour l'apprentissage de Git.

Liste des commandes :

```
git config user.email "mail" 
```
Permet de configurer l'autheur du git ainsi que l'email à qui ce dernier va être associé

```
git init
```
Permet d'initialiser et de créer le dossier .git à l'emplacement './'

```
git --version
```
Permet d'obtenir la version du git installé sur la machine
```
git branch -M main
```
Permet de définir l'emplacement './' comme le "main"

```
git tag -a "Version" -m "Message"
```
Permet de donner une version et un nom à un commit qui apparait notemment dans 'git log' (décrit ci-dessous).

```
git log 
```
Répertorie tous les anciens commit en affichant notemment leur hash, leur tag (version et nom) l'auteur (user + email), et la date de création du commit.

```
git status
```
Donne l'état du git, les fichiers pas encore 'commit' et les fichiers pas encore 'add'.
```
git add 
```
Permet de rajouter un fichier donné sur le repository (à enregistrer avec 'git commit')

```
git commit -m "Message" 
```
Permet d'enregistrer le fichier ajouté (avec git add) dans le repository et de rajouter son titre qui sera visible dans 'git log"

```
git tag -d "Version"
```
Permet de supprimer le tag précédemment ajouté sur un commit

 ```
git show
```
Permet d'avoir des informations plus précises sur le dernier commit enregistré