# Portfolio CV — Christi

Page CV en HTML5 sémantique et CSS Flexbox (sans framework), réalisée dans le cadre
du devoir Front-End de l'Université Numérique du Gabon (UNG).

## Structure du projet

```
cv-portfolio/
├── index.html      → structure HTML5 sémantique (5 sections)
├── style.css        → mise en page 100% Flexbox + responsive
└── assets/
    ├── photo-profil.jpg
    ├── cv-christi.pdf
    ├── projet-1.jpg
    ├── projet-2.jpg
    └── projet-3.jpg
```

## Avant de publier — à personnaliser

1. Remplace `assets/photo-profil.jpg` par ta vraie photo.
2. Ajoute ton CV en PDF sous `assets/cv-christi.pdf`.
3. Remplace les images `projet-1.jpg`, `projet-2.jpg`, `projet-3.jpg` par des
   captures de tes vrais projets.
4. Dans `index.html`, remplace les liens GitHub / LinkedIn / email du footer
   par les tiens.
5. Adapte le texte de la bio et des projets si besoin.

## Workflow Git & déploiement (à faire toi-même, dans un terminal)

### 1. Initialiser le dépôt et faire au moins 3 commits

```bash
cd cv-portfolio
git init
git add index.html
git commit -m "feat: structure HTML sémantique"

git add style.css
git commit -m "style: mise en page Flexbox et responsive"

git add assets
git commit -m "assets: ajout des images et du CV"
```

### 2. Créer le dépôt sur GitHub et pousser le code

- Va sur github.com → **New repository** → nomme-le par exemple `portfolio-cv`
  → laisse-le public → ne coche aucune case d'initialisation.
- Puis dans ton terminal :

```bash
git remote add origin https://github.com/TON-PSEUDO/portfolio-cv.git
git branch -M main
git push -u origin main
```

### 3. Activer GitHub Pages

- Dans le dépôt sur GitHub : **Settings → Pages**
- Source : branche `main`, dossier `/ (root)`
- Sauvegarder → le lien apparaît sous la forme :
  `https://ton-pseudo.github.io/portfolio-cv/`

### 4. Rendu

Récupère ce lien et soumets-le pour la correction, avec le lien de ton
dépôt GitHub.

## Rappel du barème (20 pts)

- Structure HTML5 (4 pts) : balises sémantiques + `alt` sur toutes les images ✔
- Flexbox & CSS (5 pts) : alignement propre, pas de débordement ✔
- Git & GitHub (3 + 2 pts bonus) : dépôt public, README clair, ≥2 commits,
  site publié via GitHub Pages → **à faire toi-même selon les étapes ci-dessus**
