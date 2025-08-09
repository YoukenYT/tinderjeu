# SwipeJeux — Prototype

Ceci est un prototype simple "Tinder pour jeux vidéo".

## Tester localement

1. Télécharge le dossier et ouvre un terminal dans ce dossier.
2. Installer les dépendances:
   ```bash
   npm install
   ```
3. Lancer le serveur de développement:
   ```bash
   npm run dev
   ```
4. Ouvre le lien affiché (généralement http://localhost:5173).

## Déployer sur Vercel

1. Crée un compte sur https://vercel.com (ou connecte-toi).
2. Clique sur **New Project** → Import Git Repository.
3. Pousse ce dossier sur GitHub (ou GitLab) et sélectionne le repo.
4. Vercel détectera automatiquement Vite + React. Clique Deploy.
5. Ton site sera en ligne via une URL vercel.app.

---

### Remarques
- Les images utilisées sont chargées depuis Internet (RAWG / Wikipedia). Si une image ne s'affiche pas, c'est normal.
- Les likes/dislikes sont stockés dans le `localStorage` de ton navigateur.
- Tu peux copier le profil (JSON) via le bouton "Copier profil".

