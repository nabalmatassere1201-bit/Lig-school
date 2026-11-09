# LIG Scolaire — déploiement

## Vercel
npm i -g vercel
vercel login
vercel --prod        # depuis ce dossier (vercel.json sert le dossier public/)

## Firebase Hosting
npm i -g firebase-tools
firebase login
firebase projects:create mon-lig-scolaire   # ou utiliser un projet existant
# remplacer VOTRE-ID-PROJET-FIREBASE dans .firebaserc, ou : firebase use --add
firebase deploy --only hosting
