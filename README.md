# HAX907X

Ce dépot contient les TPs et rapports correspondants à rendre dans le cadre du cours HAX907X.
Chaque sous-dossier contient donc un TP, son rapport, le notebook dont il est issu ainsi que les dépendences nécessaires au bon fonctionnement des différents programmes.

Pour pouvoir exécuter le code fourni, installez les dépendences à l'aide de la commande suivante:

```bash
$ pip install -r requirements.txt
```

Et pour compiler le fichier Quarto qui générera alors le rapport:

```bash
$ quarto render tp.qmd
```

Une alternative et de compiler directement le notebook:

```bash
$ quarto render tp.ipynb --execute
```

Par soucis de lisibilité et pour éviter d'avoir des rapports de plusieurs dizaines de pages, le rapport ne présente pas ou peu le code.
Le fichier .qmd étant une copie conforme du notebook il suffit alors de lancer le notebook pour voir le code en action.

## Auteur

- Thibault FERRETTI
