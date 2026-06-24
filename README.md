# Présentation vidéo FEATZY — Vercel

## Structure

- `index.html` : la présentation complète en HTML et CSS.
- `assets/logo.png` : emplacement du logo.
- `assets/video_1.mp4` : emplacement de la vidéo 1.
- `assets/video_2.mp4` : emplacement de la vidéo 2.
- `assets/poster_video_1.svg` et `assets/poster_video_2.svg` : images affichées si les vidéos ne sont pas encore ajoutées.

## À faire avant de déployer

1. Remplacer `assets/logo.png` par ton vrai logo, en gardant exactement le même nom.
2. Ajouter ta première vidéo dans `assets` avec le nom exact : `video_1.mp4`.
3. Ajouter ta deuxième vidéo dans `assets` avec le nom exact : `video_2.mp4`.
4. Ouvrir `index.html` en local pour vérifier que tout s’affiche bien.
5. Envoyer le dossier sur GitHub puis importer le repo dans Vercel.

## Notes importantes

- Le texte de placeholder sur les vidéos a été retiré.
- Les lecteurs vidéo gardent un ratio vertical 9:16.
- Les vidéos sont en `object-fit: contain`, donc elles ne seront pas coupées.
- Le site est statique : pas besoin de framework, pas besoin de build.
