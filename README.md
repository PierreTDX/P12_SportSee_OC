# SportSee

![Logo SportSee](./src/assets/img/logo.svg)

En pleine croissance, l’entreprise va aujourd’hui lancer une nouvelle version de la page profil de l’utilisateur.

Cette page va notamment permettre à l’utilisateur de suivre le nombre de sessions réalisées ainsi que le nombre de calories brûlées.  
  
> [!NOTE]  
> L'application est optimisée pour une résolution d’au moins 1024 par 780 pixels.  
> (pas de responsive mobile pour le momment)

# ![logo react](./src/assets/img/react.png) React + ![logo vite](./src/assets/img/vite.png) Vite

Ce projet est une application React configurée avec Vite.

## Prérequis

Avant de commencer, vous devez avoir installé les éléments suivants sur votre machine :

- **Node.js**
- **npm**

## Installation

Suivez les étapes ci-dessous pour configurer ce projet localement :

1. Clonez le dépôt du projet :
   ```bash
   git clone https://github.com/PierreTDX/P12_SportSee_FRONT_OC.git

2. Allez dans le dossier du projet :
   ```bash
   cd nom-du-dossier

3. Installez les dépendances du projet :
   ```bash
   npm install

4. Configurer le fichier '.env' : 
  
   Pour le développement :
   ```env
   VITE_API_BASE_URL=http://localhost:3000
   VITE_USE_MOCK_DATA=true
   ```
   => Installez l'API en local : [https://github.com/PierreTDX/P12_SportSee_BACK_OC.git](https://github.com/PierreTDX/P12_SportSee_BACK_OC.git)

   Pour la mise en production :
   ```env
   VITE_API_BASE_URL=https://p12-sport-see-back-oc.vercel.app
   VITE_USE_MOCK_DATA=false
   ```
   => ou utilisez l'API en ligne (si disponible) : [https://p12-sport-see-back-oc.vercel.app](https://p12-sport-see-back-oc.vercel.app)

## Lancer l'application

Pour démarrer l'application en mode développement, exécutez la commande suivante :
   ```bash
   npm run dev
   ```

## Build pour la production

Pour créer une version optimisée de l'application pour la production, exécutez :
   ```bash
   npm run build
   ```
   Cette commande génère un dossier dist/ contenant tous les fichiers nécessaires pour déployer l'application.

## Structure du Projet

Voici un aperçu de la structure du projet :
   ```bash
   /src                  # Dossier contenant le code source de l'application
      /api               # Dossier contenant la connexion aux différentes routes de l'API ou aux données mockées
      /assets            # Images et autres ressources
      /components        # Composants React réutilisables
      /data              # Les données mockées (pour usage en développement)
      /hooks             # Dossier contenant les hooks personnalisés (ici un hook pour la scrollbar)
      /pages             # Composants pour les pages de l'application
      /utils             # Dossier contenant les fonctions utilitaires et variables globales CSS
      App.jsx            # Composant principal de l'application
      main.jsx           # Point d'entrée de l'application
   /vite.config.js       # Fichier de configuration de Vite
   /package.json         # Dépendances et scripts
   /vercel.json          # Fichier de configuration de Vercel (pour le déploiement)
   ```

## Déploiement

Ce projet est prêt à être déployé sur Vercel  
Pour déployer le projet sur Vercel, suivez ces étapes :

- Poussez votre code vers GitHub ou GitLab.
- Connectez votre dépôt à Vercel.
- Vercel détectera automatiquement qu'il s'agit d'une application React et lancera le processus de déploiement.  

L'application est dépoyée ici : [https://p12-sport-see-oc.vercel.app/](https://p12-sport-see-oc.vercel.app/)

## Technologies utilisées

- **React**          - Framework JavaScript pour la création d'interfaces utilisateur.
- **Vite**           - Outil de build rapide pour les applications React.
- **React Router**   - Gestionnaire de routage pour la navigation entre les pages.
- **Recharts**       - Bibliothèque de graphiques basée sur React.
- **SASS**           - Préprocesseur CSS pour une meilleure gestion des styles.

## Aperçu de l'application

![Aperçu de SportSee](./src/assets/img/Screenshot.png)
