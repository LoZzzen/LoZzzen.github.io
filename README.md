# Portfolio — Stephen Losio

## Structure du projet

```
portfolio/
│
├── index.html              ← Page principale
│
└── assets/
    ├── css/
    │   └── style.css       ← Tous les styles (variables, composants, responsive)
    │
    ├── js/
    │   └── main.js         ← Cursor, scroll reveal, navbar shrink, active links
    │
    └── img/
        └── (ajouter ici ta photo de profil, favicon, og:image...)
```

## Déploiement sur GitHub Pages

1. Copier tous les fichiers dans ton repo `lozzzen.github.io`
2. Conserver la structure des dossiers `assets/css/` et `assets/js/`
3. Push sur la branche `main`
4. Le site sera live sur `https://lozzzen.github.io`

## Personnalisation rapide

| Ce que tu veux changer     | Fichier              | Ligne / Variable         |
|---------------------------|----------------------|--------------------------|
| Couleur accent verte      | `assets/css/style.css` | `--accent: #00ffa0`     |
| Couleur accent bleue      | `assets/css/style.css` | `--accent2: #00c8ff`    |
| Fond principal            | `assets/css/style.css` | `--bg: #080b0f`         |
| Ajouter un projet         | `index.html`          | Section `#projets`       |
| Modifier les expériences  | `index.html`          | Section `#experience`    |
| Ajouter une certification | `index.html`          | Section `#certifications`|
| Animations JS             | `assets/js/main.js`   | Cursor / Observer        |
