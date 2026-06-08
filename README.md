# Pascal IA — Tuteur Histoire Seconde

## Déploiement Railway (3 étapes)

1. Push ce repo sur GitHub
2. Railway → New Project → Deploy from GitHub → sélectionne ce repo
3. Railway → Variables → ajoute `ANTHROPIC_API_KEY` = ta clé Claude

C'est tout. Railway détecte automatiquement Node.js et lance `npm start`.

## Structure
```
pascal-ia/
├── src/server.js      ← Backend + Prompt Pascal complet
├── public/index.html  ← Frontend immersif
├── package.json
├── .env.example
└── .gitignore
```

## Variables d'environnement
```
ANTHROPIC_API_KEY=sk-ant-...
PORT=3000 (géré automatiquement par Railway)
```
