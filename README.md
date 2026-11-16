# Site VIZA

Site vitrine de VIZA, agence de communication 360° et imprimerie à Abidjan.
Hébergé gratuitement par GitHub Pages ; contenus modifiables avec le CMS intégré.

## Modifier le site

1. Ouvrez l'adresse du site suivie de `?admin` (exemple : `https://votre-compte.github.io/viza/?admin`).
2. Cliquez sur **Modifier le site** (en bas à gauche).
3. La première fois, collez votre jeton GitHub (voir plus bas). Il reste enregistré dans ce navigateur.
4. Modifiez textes, listes et images : l'aperçu est en direct.
5. Cliquez sur **Publier**. Le site en ligne est à jour en une à deux minutes.

Sur un autre appareil, refaites l'étape 3 avec le même jeton (ou un nouveau).

## Créer le jeton GitHub (une seule fois)

1. github.com › photo de profil › **Settings** › **Developer settings** › **Personal access tokens** › **Fine-grained tokens** › **Generate new token**.
2. Nom : `CMS VIZA`. Expiration : la plus longue proposée.
3. **Repository access** : *Only select repositories* › choisissez le dépôt du site.
4. **Permissions** › *Repository permissions* › **Contents : Read and write**.
5. **Generate token**, copiez-le et collez-le dans le CMS. Ne le partagez avec personne.

Si le jeton expire, le CMS le signale : créez-en un nouveau et collez-le.

## Contenu du dépôt

- `index.html` : le site complet (pages, styles, contenus et CMS).
- `images/` : photos du site. Les images ajoutées depuis le CMS vont dans `images/cms/`.
- `favicon.svg`, `images/og.png` : icône d'onglet et visuel de partage sur les réseaux.
- `robots.txt`, `sitemap.xml` : référencement Google.
