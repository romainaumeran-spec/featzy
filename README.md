# Présentation vidéo FEATZY — Vercel

## Structure

- `index.html` : page principale à déployer.
- `assets/logo.png` : emplacement du logo. Remplace ce fichier par ton logo.
- `assets/video_1.mp4` : emplacement de la vidéo 1.
- `assets/video_2.mp4` : emplacement de la vidéo 2.
- `assets/poster_video_1.svg` et `assets/poster_video_2.svg` : visuels affichés tant que les vidéos ne sont pas chargées.

## Intégrer les vidéos

1. Ouvre le dossier `assets`.
2. Ajoute tes vidéos au format MP4.
3. Renomme-les exactement :
   - `video_1.mp4`
   - `video_2.mp4`
4. Remplace `logo.png` par ton vrai logo, en gardant le même nom de fichier.

## Déployer sur Vercel

### Option simple avec GitHub

1. Dézippe ce dossier.
2. Mets le dossier dans un repo GitHub.
3. Sur Vercel, clique sur `Add New Project`.
4. Importe le repo.
5. Laisse les réglages par défaut : aucun framework, aucun build command.
6. Vérifie que `index.html` est bien à la racine.
7. Clique sur `Deploy`.

### Option CLI

Depuis le dossier du projet :

```bash
npm i -g vercel
vercel login
vercel
```

Pour envoyer en production :

```bash
vercel --prod
```
