# Mettre en ligne la boîte à outils GLC Admin sur GitHub

Durée : environ 20 minutes. Coût : gratuit.

## 1. Créer le compte
1. Allez sur https://github.com/signup.
2. Utilisez l'adresse **contact@glc-admin.com**.
3. Choisissez le nom de compte **glc-admin** (ou **glcadmin** s'il est déjà pris). Ce nom apparaîtra dans l'adresse du site.
4. Choisissez l'offre gratuite (Free).

## 2. Créer le dépôt
1. Cliquez sur **+** en haut à droite, puis **New repository**.
2. Nom du dépôt :
   - **glc-admin.github.io** (remplacez *glc-admin* par votre nom de compte) : le site sera à l'adresse `https://glc-admin.github.io` ;
   - ou **outils** : le site sera à l'adresse `https://glc-admin.github.io/outils`.
3. Cochez **Public**. Avec le compte gratuit, GitHub Pages ne fonctionne qu'avec un dépôt public : le contenu sera visible de tous.
4. Cliquez sur **Create repository**.

## 3. Déposer les fichiers
1. Décompressez le fichier zip reçu.
2. Dans le dépôt, cliquez sur **uploading an existing file**.
3. Glissez **tout le contenu** du dossier décompressé : `index.html`, `README.md`, `.nojekyll`, le dossier `outils`, ce mode d'emploi. Glissez les fichiers eux-mêmes, pas le dossier parent.
4. Le fichier `.nojekyll` est invisible sous Windows et Mac. Si vous ne le voyez pas, ce n'est pas grave : le site fonctionne aussi sans lui.
5. En bas, cliquez sur **Commit changes**.

## 4. Activer le site
1. Dans le dépôt : **Settings**, puis **Pages** dans le menu de gauche.
2. Rubrique **Build and deployment** :
   - Source : *Deploy from a branch* ;
   - Branch : *main*, dossier */ (root)*.
3. Cliquez sur **Save**.
4. Attendez une à deux minutes : l'adresse du site s'affiche en haut de la page.

## 5. Facultatif : une adresse à votre nom (outils.glc-admin.com)
1. Dans **Settings > Pages > Custom domain**, saisissez `outils.glc-admin.com` et enregistrez.
2. Chez votre hébergeur de nom de domaine (là où est géré glc-admin.com), ajoutez un enregistrement DNS :
   - type **CNAME** ;
   - nom **outils** ;
   - valeur **glc-admin.github.io** (votre nom de compte suivi de .github.io).
3. Une fois l'adresse validée, cochez **Enforce HTTPS**.
4. Ajoutez un lien vers `https://outils.glc-admin.com` sur glc-admin.com.

## Mettre à jour un outil
Ouvrez le fichier dans GitHub, cliquez sur l'icône crayon ou sur **Add file > Upload files**, déposez la nouvelle version au même endroit, puis **Commit changes**. Le site se met à jour en une à deux minutes.

## À savoir avant de publier
- **Code visible :** un dépôt public permet à n'importe qui de voir et de télécharger le code des outils. Si vous préférez garder les versions complètes pour vos clients, ne publiez que la page vitrine (`index.html`) et remplacez les boutons « Essayer l'outil » par un lien de contact ou une vidéo de démonstration.
- **Droits :** le README indique « Tous droits réservés ». N'ajoutez pas de licence libre si vous voulez garder la main sur la réutilisation.
- **Données :** les outils fonctionnent dans le navigateur de la personne qui les ouvre. Les fichiers qu'elle traite ne sont jamais envoyés à GitHub ni à vous.
