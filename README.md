# Notes de version GEEF / Virtualia — version Word

Ce dépôt public héberge les **notes de version au format Word** (« Version Word illustrée ») de GEEF et Virtualia.
Il n'y a rien à lire dans le code : les documents sont les fichiers joints de la release
[**notes-word**](https://github.com/GEEF-Virtualia/geef-docs-word/releases/tag/notes-word).

📖 Les notes de version se consultent sur le site de documentation :
**https://geef-virtualia.github.io/geef-docs/**. Chaque page de version propose le bouton
« 📌 VERSION WORD ILLUSTREE », qui pointe vers le Word de ce dépôt.

## Télécharger une note de version

Chaque version a son fichier, nommé d'après son numéro :

```
https://github.com/GEEF-Virtualia/geef-docs-word/releases/download/notes-word/<version>.docx
```

Par exemple, [6.1.docx](https://github.com/GEEF-Virtualia/geef-docs-word/releases/download/notes-word/6.1.docx) pour la
version 6.1, ou [6.0.1.docx](https://github.com/GEEF-Virtualia/geef-docs-word/releases/download/notes-word/6.0.1.docx)
pour la version 6.0.1. La liste complète figure sur la page de la release.

Le téléchargement ne demande pas de compte GitHub.

## D'où viennent ces fichiers

Les Word sont rédigés et générés dans le dépôt de la documentation (privé), dossier `docs/downloads/`. À chaque
publication du site, son workflow « Publication du site » les envoie ici :

- un Word nouveau ou modifié est ajouté ou remplacé ; les autres ne sont pas renvoyés ;
- un Word remplacé garde le même nom, donc la même adresse : les liens déjà diffusés restent valables ;
- aucun fichier n'est supprimé automatiquement.

**Ne rien déposer ni modifier à la main dans ce dépôt ou dans sa release** : la prochaine publication écraserait
les changements. Toute correction se fait dans le dépôt de la documentation.

## Contact

Pour une question sur une note de version, s'adresser à l'équipe GEEF / Virtualia de Cegape.
