# PwaForge

A streamlined, browser-based tool to "forge" Progressive Web Apps and deploy them instantly to GitHub and Vercel.

## 🚀 Features

* **PWA Manifest Generation**: Automatically creates `manifest.json` with custom icons and theme colors.
* **Service Worker Integration**: Injects a functional Service Worker for offline capabilities.
* **Automated Forge**: 
    * Creates a new repository on your **GitHub** account.
    * Synchronizes project files via the GitHub API.
    * Deploys the static site to **Vercel** with a live URL.
* **Asset Management**: Real-time icon resizing (192x192 and 512x512) using HTML5 Canvas.

## 🛠 Configuration

To use the automated deployment, you must provide:
1.  **GitHub Token**: A Personal Access Token (PAT) with `repo` scope.
2.  **Vercel Token**: A Vercel API token from your account settings.

## 📖 How to Use

1.  Enter your app identity (Name, Colors).
2.  Upload a source image for the icon.
3.  Edit your `index.html` directly in the built-in editor.
4.  Click **"Déployer"** (Deploy) to start the automated flow.

---

# PWA Forge & Deploy | Édition Seigneur Bison

Un outil de forge directement dans le navigateur pour concevoir des Progressive Web Apps et les déployer instantanément sur GitHub et Vercel.

## 🚀 Fonctionnalités

* **Génération de Manifeste PWA** : Crée automatiquement le fichier `manifest.json` avec vos icônes et couleurs personnalisées.
* **Intégration de Service Worker** : Injecte un Service Worker fonctionnel pour la gestion du mode hors-ligne.
* **Forge Automatisée** : 
    * Crée un nouveau dépôt sur votre compte **GitHub**.
    * Synchronise les fichiers du projet via l'API GitHub.
    * Déploie le site statique sur **Vercel** avec une URL publique.
* **Gestion des Assets** : Redimensionnement des icônes en temps réel (192x192 et 512x512) via HTML5 Canvas.

## 🛠 Configuration

Pour utiliser le déploiement automatisé, vous devez fournir :
1.  **Token GitHub** : Un jeton d'accès personnel (PAT) avec les permissions `repo`.
2.  **Token Vercel** : Un jeton API Vercel généré depuis les paramètres de votre compte.

## 📖 Utilisation

1.  Saisissez l'identité de votre application (Nom, Couleurs).
2.  Téléchargez une image source pour l'icône.
3.  Modifiez votre `index.html` directement dans l'éditeur intégré.
4.  Cliquez sur **"Déployer"** pour lancer le flux automatisé.

---

## Todo
- Connecter le repo github te l'hebergement vercel automatiquement
- Renvoyer le bon lien dans la console et l'afficher joliment sur le site
- Détecter automatiquement les couleurs de l'icone pour en faire les couleurs de la pwa
