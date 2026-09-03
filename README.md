# Portfolio Data Analyst

Site statique prêt à personnaliser et à publier sur GitHub Pages.

## Contenu

- `index.html` — page d’accueil
- `projects/` — 5 case studies
- `css/style.css` — design
- `js/main.js` — menu mobile + année

## Personnaliser

Remplace partout :

- `Prénom Nom`
- `prenom.nom@email.com`
- `https://github.com/TON-USERNAME`
- `https://www.linkedin.com/in/TON-PROFIL`
- le logo `PN.`
- les textes “À propos” et les liens GitHub dans chaque projet

## Publier sur GitHub Pages

```bash
cd portfolio
git init
git add .
git commit -m "Premier commit portfolio"
```

Crée un repo `prenom-nom.github.io` (ou un repo classique), pousse le code, puis active **Settings → Pages → Deploy from branch main**.

Si le site n’est pas à la racine du repo, mets le dossier `portfolio` comme racine Git, ou utilise `/docs`.

## Ensuite

1. Fais vraiment les 3–5 projets (SQL, dashboard, Python).
2. Colle les vrais insights chiffrés dans les pages projets.
3. Ajoute tes screenshots dans `projects/` si tu veux.

Le design n’est pas une copie pixel-perfect d’Alex The Analyst (template HTML5 UP Massively). C’est la même logique : accueil + projets cliquables + liens GitHub/Tableau, dans une version plus actuelle et en français.
