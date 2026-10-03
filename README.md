# Velvet

Velvet est une petite maquette de site web réalisée en HTML et CSS. Elle sert de base de travail pour explorer une mise en page responsive, des cartes et un formulaire dans un thème sombre avec des accents vert lime.

## Aperçu

La page comprend :

- un en-tête avec une navigation ;
- une section principale avec trois cartes de présentation ;
- une barre latérale avec un formulaire ;
- un pied de page ;
- une mise en page qui s'adapte aux petits écrans.

## Lancer le projet

Aucune installation ni dépendance n'est nécessaire. Ouvrez simplement `frontend/index.html` dans un navigateur.

Pour servir la page en local avec Python, vous pouvez aussi lancer depuis le dossier `frontend` :

```bash
python -m http.server 8000
```

Puis ouvrez [http://localhost:8000](http://localhost:8000).

## Structure

```text
.
├── frontend/
│   ├── index.html   # Page principale
│   └── style.css    # Styles et mise en page responsive
├── backend/         # Espace réservé au futur backend
└── README.md
```

## État actuel

Le projet est un prototype front-end. Les liens de navigation sont des exemples et le formulaire n'envoie ni ne stocke encore de données. Le dossier `backend` est présent, mais ne contient pas d'implémentation pour le moment.