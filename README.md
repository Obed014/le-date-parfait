```markdown
# 💕 Le Date Parfait - Haïti

<div align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-pink.svg" alt="Version">
  <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome">
</div>

## 🌟 À propos

**Le Date Parfait** est une plateforme web qui aide les Haïtiens à découvrir les meilleurs endroits pour leurs rendez-vous romantiques. Restaurants, hôtels, événements, conseils - tout en un seul endroit !

🌐 **[Voir la démo en ligne](https://votre-username.github.io/le-date-parfait/)**

## ✨ Fonctionnalités

- 🗺️ **Banque de lieux** - Restaurants, hôtels, boutiques, fleuristes
- 📅 **Calendrier d'événements** - Concerts, vernissages, pool parties
- ⭐ **Système d'avis** - Notes et commentaires des utilisateurs
- 📧 **Newsletter** - Restez informé des nouveautés
- 📱 **PWA** - Installable comme une application mobile
- 🌐 **Géolocalisation** - Liens vers Google Maps
- 📞 **Informations de contact** - Téléphone, site web, horaires
- 🔧 **CMS Admin** - Panneau d'administration complet
- 💾 **Stockage local** - Données persistantes

## 🚀 Installation

### 1. Cloner le projet

```bash
git clone https://github.com/VOTRE-USERNAME/le-date-parfait.git
cd le-date-parfait
```

### 2. Ouvrir localement

Ouvrez simplement `index.html` dans votre navigateur !

### 3. Ou utiliser un serveur local

```bash
# Avec Python
python -m http.server 8000

# Avec Node.js
npx http-server

# Avec PHP
php -S localhost:8000
```

Puis ouvrez : `http://localhost:8000`

## 📱 Installation comme PWA

1. Ouvrez le site dans Chrome/Safari
2. Cliquez sur le bouton "Installer l'app"
3. L'icône apparaîtra sur votre écran d'accueil !

## 🎯 Utilisation

### Pour les visiteurs

- **Explorez** les lieux par catégorie
- **Recherchez** par nom ou localisation
- **Consultez** les avis et notes
- **Abonnez-vous** à la newsletter

### Pour les contributeurs

1. Connectez-vous
2. Ajoutez vos lieux favoris
3. Laissez des avis
4. Vos contributions seront modérées

### Pour les administrateurs

**Email:** `admin@ledateparfait.ht`

Accès au CMS complet :
- ⚙️ Paramètres du site
- 🏷️ Gestion des catégories
- 📍 Gestion des lieux
- 🎉 Gestion des événements
- 📧 Newsletter
- ✅ Modération

## 🛠️ Technologies

- **Frontend:** React 18
- **Styling:** Tailwind CSS
- **Icons:** Lucide Icons
- **Storage:** LocalStorage
- **PWA:** Service Workers

## 📂 Structure du code

```
le-date-parfait/
├── index.html          # Application principale
├── sw.js              # Service Worker (offline)
├── manifest.json      # PWA Manifest
└── README.md          # Documentation
```

## 🌐 Déploiement

### GitHub Pages (Gratuit)

1. Poussez votre code sur GitHub
2. Allez dans **Settings** → **Pages**
3. Source: `main` branch
4. Votre site sera sur : `https://VOTRE-USERNAME.github.io/le-date-parfait/`

### Netlify (Gratuit)

1. Connectez votre repo GitHub
2. Deploy automatique à chaque commit
3. HTTPS gratuit + domaine personnalisé

### Vercel (Gratuit)

Même processus que Netlify

## 🔐 Sécurité

- Pas de données sensibles côté client
- Validation des entrées utilisateur
- Protection XSS avec React
- HTTPS obligatoire en production

## 🐛 Problèmes connus

- Les données sont stockées localement (pas de sync entre appareils)
- Les emails sont simulés (intégrer Mailgun en production)
- Les images sont des emojis (ajouter upload en production)

## 🚧 Roadmap

- [ ] Backend Node.js + MongoDB
- [ ] Upload d'images réelles
- [ ] Système de paiement
- [ ] Application mobile native (React Native)
- [ ] API RESTful
- [ ] Authentification JWT
- [ ] Chat en temps réel

## 🤝 Contribuer

Les contributions sont bienvenues !

1. Fork le projet
2. Créez votre branche (`git checkout -b feature/AmazingFeature`)
3. Commit (`git commit -m 'Add AmazingFeature'`)
4. Push (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

## 📄 Licence

MIT License - Libre d'utilisation

## 👨‍💻 Auteur

**Votre Nom**
- GitHub: [@votre-username](https://github.com/votre-username)
- Email: votre@email.com

## 💖 Remerciements

- Communauté React
- Tailwind CSS
- Lucide Icons
- Tous les contributeurs

---

<div align="center">
  Fait avec ❤️ en Haïti 🇭🇹
</div>
```
