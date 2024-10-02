# COURS

## Bases

### Les Repositories

C'est un dossier, qui travaille avec GIT

Pour transformer un dossier en repo, il faut au choix :

- ```git init``` : qui permet d'initialiser un repo
- ```git clone [URL]``` : qui permet de créer un repo et un dossier à partir d'une URL

Un repo local : sur la machine
Un repo distant : sur un serveur (gitlab, github, etc...)

### Le triptique de base

```git add .``` : permet d'ajouter tous les fichiers ajoutés ou modifiés ou supprimés en "staging"
```git commit -m "message..."``` : création de l'enregistrement **du staging** !
```git push``` : mettre en ligne les commits réalisés