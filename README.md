# ENSA Beni Mellal - Portail Étudiant

Ce projet est un portail étudiant pour l'École Nationale des Sciences Appliquées de Beni Mellal (ENSA-BM). Il permet aux étudiants de consulter leurs emplois du temps, projets, examens et autres informations importantes.

## Fonctionnalités

- **Authentification** : Connexion sécurisée pour les étudiants et les administrateurs
- **Tableau de bord étudiant** : Vue d'ensemble des informations importantes
- **Emplois du temps** : Consultation des emplois du temps par filière et année
- **Projets et deadlines** : Suivi des projets et des échéances
- **Examens** : Calendrier des examens
- **Espace administrateur** : Gestion des étudiants, professeurs, modules et emplois du temps

## Technologies utilisées

- **Frontend** : React, CSS, JavaScript, Vite
- **Backend** : Node.js, Express
- **Base de données** : MongoDB
- **Authentification** : JWT (JSON Web Tokens)

## Installation

### Prérequis

- Node.js (v14 ou supérieur)
- npm ou yarn
- MongoDB

### Installation du frontend

```bash
# Cloner le dépôt
git clone https://github.com/votre-username/ensabm-student-portal.git
cd ensabm-student-portal

# Installer les dépendances
npm install

# Lancer l'application en mode développement
npm run dev
```

### Installation du backend

```bash
# Naviguer vers le dossier backend
cd backend

# Installer les dépendances
npm install

# Créer un fichier .env avec les variables d'environnement nécessaires
# Exemple:
# MONGO_URI=mongodb://localhost:27017/ensabm
# JWT_SECRET=votre_secret_jwt
# PORT=5000

# Lancer le serveur
npm start
```

## Captures d'écran

[Ajoutez des captures d'écran de votre application ici]

## Contributeurs

- [Hamza-El-Mourabit](https://github.com/Hamza-El-Mourabit)

## Licence

Ce projet est sous licence MIT.
