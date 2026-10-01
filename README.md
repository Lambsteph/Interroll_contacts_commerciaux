# Guide de contact Interroll France — déploiement Render

Ce dossier contient une page HTML autonome prête à être publiée comme **Static Site** sur Render.

## Contenu

- `index.html` : le guide de contact complet.
- `render.yaml` : configuration optionnelle pour un déploiement Render Blueprint.

## Déploiement depuis le tableau de bord Render

1. Créez un nouveau dépôt GitHub, par exemple `interroll-guide-contact`.
2. Ajoutez les fichiers de ce dossier à la racine du dépôt.
3. Dans Render, choisissez **New > Static Site**.
4. Connectez le nouveau dépôt GitHub.
5. Utilisez les réglages suivants :
   - **Branch** : `main`
   - **Root Directory** : laisser vide
   - **Build Command** : `echo "Site statique prêt"`
   - **Publish Directory** : `.`
6. Cliquez sur **Create Static Site**.
7. Lorsque le déploiement est terminé, ouvrez l'adresse `https://...onrender.com` fournie par Render.

Ce déploiement crée un site séparé et ne modifie pas les autres services Render.
