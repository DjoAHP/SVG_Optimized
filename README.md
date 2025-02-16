## Scripts disponibles

Voici les scripts disponibles dans le fichier `package.json` :

- **`npm run optimize`**: Ce script optimise tous les fichiers SVG présents dans le dossier `src/SVG`. Il parcourt chaque fichier SVG dans ce dossier, applique des règles d'optimisation pour réduire leur taille tout en conservant leur qualité visuelle, puis sauvegarde les versions optimisées dans le dossier `src/SVG_Optimized`.

- **`npm run optimize:file`**: Ce script est conçu pour optimiser un seul fichier SVG spécifique. Par exemple, si vous avez un fichier nommé `your-icon.svg` dans le dossier `src/SVG`, exécuter `npm run optimize:file` optimisera ce fichier particulier et sauvegardera la version optimisée sous le nom `your-icon-optimized.svg` dans le dossier `src/SVG_Optimized`.

Dossier complet:
```bash
npm run optimize
```
Fichier cibler:
```bash
npm run optimize:file
```