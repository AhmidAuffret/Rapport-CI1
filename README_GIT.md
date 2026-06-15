# Méthode Git du projet

## Principe

La branche `main` contient uniquement les éléments validés.

Le travail doit être fait dans des branches dédiées :

- une branche par tâche ;
- une branche par section ;
- pas une branche par PC.

## Workflow recommandé

Avant de commencer :

```bash
git checkout main
git pull
git checkout -b nom-de-la-tache
```

Après modification :

```bash
git add .
git commit -m "Message clair"
git push -u origin nom-de-la-tache
```

Après relecture, fusionner dans `main`.

## Règles

- Ne pas travailler directement sur `main`.
- Faire des commits courts et compréhensibles.
- Ne pas versionner de documents confidentiels bruts.
- Ne pas versionner de mots de passe ou secrets.
- Utiliser `[REDACTED]` pour les informations sensibles.
