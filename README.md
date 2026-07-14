# Loca-Wedding

Site vitrine — Location & Décoration de Mariage (Belgique).

Site statique autonome en un seul fichier `index.html` (React + Babel chargés via CDN, aucune étape de build nécessaire).

## Éditer le contenu

Tous les textes et images du site sont centralisés dans le bloc `TWEAK_DEFAULTS` en haut du fichier (`const TWEAK_DEFAULTS = {...}`). Chaque produit du catalogue a sa propre clé image (`img_p1` à `img_p39`), ainsi que les photos des catégories (`img_cat_*`) et des pages (`img_hero`, `img_about`, etc.).

Pour prévisualiser en local : ouvrir `index.html` dans un navigateur, ou utiliser l'extension VSCode "Live Server" pour un rafraîchissement automatique à chaque sauvegarde.

## Déploiement

Ce repo est connecté à Netlify. Chaque `git push` sur la branche `main` déclenche un redéploiement automatique du site — aucune configuration de build requise (fichier statique à la racine).
