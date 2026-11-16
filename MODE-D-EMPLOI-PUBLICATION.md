# Publier ou mettre à jour le site GLC Admin

## Adresse du site
Pour que le site soit à l'adresse `https://glc-administration.github.io`, le dépôt doit s'appeler **GLC-administration.github.io**
(Settings > General > Repository name). Avec un autre nom, le site est à l'adresse `https://glc-administration.github.io/NOM-DU-DEPOT/`.

## Activer la publication
Settings > Pages > Source « Deploy from a branch » > Branch « main » et dossier « /docs » > Save. Le site doit donc toujours se trouver dans le dossier `docs/`.

## Mettre à jour à la main
1. Décompressez le zip reçu.
2. Dans le dépôt, ouvrez le dossier `docs`, puis Add file > Upload files.
3. Glissez **le contenu** du dossier décompressé, dossiers compris (avec Chrome ou Edge). Ne glissez ni le zip, ni le dossier parent.
4. Commit changes. Le site se met à jour en une à deux minutes.

## Logo
Le logo se trouve dans `docs/assets/logo-glc-admin.png` (PNG à fond transparent). Tant qu'il est absent, le texte « GLC Admin » s'affiche à sa place.

## À savoir
- Dépôt public : le code des outils est visible et téléchargeable par tous.
- Les fichiers que les visiteurs traitent dans les outils ne sont envoyés ni à GitHub, ni à vous.
