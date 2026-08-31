# BV Détail Pro

Ce dépôt est prêt pour un déploiement statique sur Vercel.

## Organisation

- `public/` : seuls les fichiers de ce dossier sont publiés sur Vercel. La page d'entrée est `public/index.html`.
- `BV Détail Pro_files/` : ressources brutes importées dans le dépôt. Elles ne sont pas incluses dans le déploiement, car elles ne contiennent pas la page du site.
- `vercel.json` : indique à Vercel de publier `public/` sans étape de compilation.

Pour publier le vrai site, placez son `index.html` et ses ressources nécessaires dans `public/` en conservant leurs chemins relatifs.
