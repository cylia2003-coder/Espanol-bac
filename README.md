# Español — Application mobile (PWA)

Application web installable sur Android et iOS, conçue pour être publiée avec **GitHub Pages**.

## Publier sur GitHub Pages
1. Crée un dépôt GitHub, par exemple `espanol-bac`.
2. Décompresse ce ZIP et envoie **le contenu du dossier `espanol-mobile`** à la racine du dépôt (le fichier `index.html` doit être à la racine).
3. Dans GitHub : **Settings → Pages**.
4. Choisis **Deploy from a branch**, puis `main` et `/ (root)`, et enregistre.
5. Attends la publication et ouvre l'adresse GitHub Pages sur ton téléphone.
6. Dans Chrome Android : menu ⋮ → **Installer l'application** (ou **Ajouter à l'écran d'accueil**).

## Fonctionnement hors ligne
Le service worker met en cache l'application et ses icônes après le premier chargement. Le premier accès nécessite une connexion. Les polices distantes peuvent ne pas être disponibles hors ligne.

## Icône
L'icône est l'illustration fournie (danseuse, voile blanc, roses rouges), générée dans `assets/` :
`icon-192.png`, `icon-512.png` (any), `icon-maskable-512.png` (Android adaptatif), `apple-touch-icon.png` (iOS, 180×180), `favicon.ico` / `favicon-32.png`.
La source fournie faisait 180×180 px : les versions 192/512 sont agrandies et donc un peu douces. Pour un rendu parfaitement net, remplace-les par une version haute résolution (≥ 1024 px) en gardant les mêmes noms.

## Notes
- Nom de l'application : **Español**.
- La progression pédagogique reste enregistrée localement dans le navigateur/appareil.
- Ce projet est une PWA, pas encore un APK Android natif.
