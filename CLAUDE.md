# Business Finder - Projet

## Description
Site web pour trouver des business sans sites web, avec système d'authentification et abonnement premium.

## Fichiers principaux
- `index.html` — Fichier unique contenant tout le code (HTML + CSS + JS)

## Fonctionnalités

### Authentification
- Login email + mot de passe (hashé en localStorage)
- Login Google (Client ID: dans le code)
- Session persiste dans localStorage
- Admin: `amranijouteiismail@gmail.com` (accès illimité, peut donner Premium)

### Abonnement
- **Gratuit**: 5 recherches/jour, max 30 résultats, basiques filtres
- **Premium**: $20 lifetime (paiement unique, accès à vie)
  - Recherches illimitées
  - Export CSV
  - Pas de pubs
  - Support prioritaire
- Pour payer: Discord `loki_ismail`, Reddit `u/loki_ismail`, Email `ismailamranijoutei@gmail.com`

### Technique
- Overpass API (OpenStreetMap) pour les recherches
- Nominatim pour le géocodage
- localStorage pour les données utilisateurs
- Pas de backend (mode demo)

## Commandes

### Lancer le site
Ouvrir `index.html` directement dans le navigateur, ou utiliser Live Server dans VS Code.

### Git
```bash
git add .
git commit -m "Description"
git push
```

### Déploiement
- Repo GitHub: https://github.com/ismailamranijoutei/Buisness-finder
- Vercel redéploie automatiquement à chaque push

## État actuel
- [x] Authentification email/Google
- [x] Système admin
- [x] Abonnement Premium $20 lifetime
- [x] Interface Free vs Premium
- [x] Message logout warning
- [x] Déployé sur Vercel

## À faire
- Ajouter les clés Stripe pour vrais paiements (optionnel)
- Ajouter plus de filtres avancés
