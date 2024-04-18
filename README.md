# SUIVI DU TOTRIEL DE NICO DEVELOP

## Initialisation du dépot

```bash
 git init
 git remote add origin SSH-REPO
```

## Rédiger un commit (bonne pratique)

```
Titre du commit

Desciption de notre commit avec des infomations sur l'évolution du projet
```

```bash
git add .
git commit -m "Un commentaire"
git push origin main
```

## Création d'une branche

```bash
git checkout -b NOM_BRANCHE
```

Pour les bonnes pratique, on va intégrer la notion de revue de code. Pour cela, on va crée une branche, faire des modifications, les envoyer sur le dêpot distant, puis créer une pull request pour demander une revue de code.
