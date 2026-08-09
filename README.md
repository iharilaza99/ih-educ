# ih-educ

Plateforme numérique pour le suivi pédagogique, l'accès aux ressources et les informations administratives des étudiants.

## À propos
ih-educ fournit une documentation statique (site MkDocs) destinée aux étudiants et au personnel pédagogique : profil de la plateforme, BUP (Bilan Unifié Pédagogique), bibliothèque numérique et informations de contact.

## Stack
- Langage principal : Markdown (site statique)
- Framework / thème : MkDocs + Material for MkDocs
- Dépendances notables : mkdocs, mkdocs-material

## Exécution locale
Prérequis : Python 3.8+, pip

```bash
pip install mkdocs mkdocs-material
mkdocs serve    # développe en local (http://127.0.0.1:8000)
mkdocs build    # génère le site statique dans le dossier site/
mkdocs gh-deploy -m "Deploy site"  # déploie sur GitHub Pages (optionnel)
```

Les pages sources se trouvent dans le dossier `docs/`. Ajoutez les ressources (PDF, images) dans `docs/assets/` puis liez-les depuis les pages Markdown.

## Contribuer
- Modifiez les fichiers Markdown dans `docs/` et testez localement avec `mkdocs serve`.
- Pour signaler un bug ou demander une fonctionnalité, ouvrez une issue sur ce dépôt.

## Licence
Ajoutez ici la licence du projet (par ex. MIT) si nécessaire.
