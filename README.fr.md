<div align="center">
  <img src="assets/images/logo.svg" alt="Logo de Pili Client" width="128" height="128" />
  <h1>Pili Client</h1>
  <p><strong>Client HTTP/REST rapide, compatible Git et respectueux de la vie privée pour Visual Studio Code et ses dérivés.</strong></p>
  <p><em>Développé avec ❤️ par <strong>Misael Arroyo</strong></em></p>

  <p>
    <a href="README.md">English</a> •
    <a href="README.es.md">Español</a> •
    <a href="README.de.md">Deutsch</a> •
    <a href="README.fr.md"><strong>Français</strong></a> •
    <a href="README.pt.md">Português</a> •
    <a href="README.zh-CN.md">简体中文</a>
  </p>

  <p>
    <a href="https://marketplace.visualstudio.com/items?itemName=PiliClient.pili-client"><img src="https://img.shields.io/badge/VS%20Marketplace-Pili%20Client-blue?logo=visual-studio-code" alt="Visual Studio Marketplace" /></a>
    <a href="https://open-vsx.org/extension/PiliClient/pili-client"><img src="https://img.shields.io/badge/Open%20VSX-Pili%20Client-purple?logo=eclipseide" alt="Open VSX" /></a>
    <a href="https://github.com/Pili-Tools/pili-client-support/releases"><img src="https://img.shields.io/badge/Release-v0.1.1-green" alt="Dernière version" /></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/Licence-Freeware-informational" alt="Licence" /></a>
  </p>
</div>

---

## ⚡ Présentation

**Pili Client** est un client d'API REST moderne, rapide et conçu pour les développeurs, intégré à **VS Code**, **Cursor**, **VSCodium**, **Windsurf** et **Eclipse Theia**.

Contrairement aux clients d'API traditionnels qui stockent vos données sur des serveurs cloud propriétaires, Pili Client conserve toutes vos collections, environnements, cookies et tests en sécurité dans le stockage global d'extensions de votre éditeur sur votre machine locale. Vos données restent ainsi indépendantes du projet ouvert et vos dépôts Git restent propres.

---

## ✨ Fonctionnalités Principales

* 🚀 **Indépendant du dossier & Dépôts propres :** Vos requêtes et environnements sont sauvegardés dans le stockage global local de votre éditeur, sans encombrer vos dépôts de code.
* 🔒 **Confidentialité totale et séparation des secrets :** 100% hors ligne et local. Vos clés d'API et mots de passe sensibles résident en toute sécurité sur votre machine.
* ⚡ **Interface réactive en Svelte :** Démarrage instantané et empreinte mémoire minimale dans l'éditeur.
* 🌐 **Sans restrictions CORS :** Les requêtes HTTP/HTTPS s'exécutent dans le processus Node.js natif.
* 🔄 **Synchronisation en direct :** Détection automatique des modifications de fichiers et mise à jour immédiate.
* 🧪 **Exécuteur de collections (Collection Runner) :** Exécution séquentielle, tests basés sur des données (CSV/JSON), assertions et rapports (HTML, JUnit).
* 🍪 **Gestionnaire de cookies et certificats :** Prise en charge des cookies de session et des certificats mTLS (PFX, PEM, CRT, KEY).
* 💻 **Générateur de code et de types :** Génération d'extraits de code (cURL, Python, PHP, Fetch, Axios) et d'interfaces TypeScript automatiques.
* 🌍 **Support multilingue complet :** Français, Anglais, Espagnol, Allemand, Portugais et Chinois simplifié.

---

## 📦 Installation

### Depuis VS Code / Cursor / Windsurf
1. Ouvrez le panneau des extensions (`Ctrl+Shift+X` ou `Cmd+Shift+X`).
2. Recherchez `Pili Client`.
3. Cliquez sur **Installer**.

### Depuis VSCodium / Open VSX
1. Ouvrez le gestionnaire d'extensions.
2. Recherchez `Pili Client` sur Open VSX et installez-le.

---

## 📁 Emplacement des Fichiers et Stockage

Par défaut, Pili Client stocke toutes vos collections, requêtes, environnements, cookies et certificats dans le répertoire officiel de stockage global de VS Code :

* **Windows :** `%APPDATA%\Code\User\globalStorage\PiliClient.pili-client`
* **macOS :** `~/Library/Application Support/Code/User/globalStorage/PiliClient.pili-client`
* **Linux :** `~/.config/Code/User/globalStorage/PiliClient.pili-client`
* **VS Code Server (Linux / Remote) :** `~/.vscode-server/data/User/globalStorage/PiliClient.pili-client`

---

## 💬 Communauté & Support

* 🐛 **Signaler un bug :** [Ouvrir un rapport](https://github.com/Pili-Tools/pili-client-support/issues/new?template=bug_report.md)
* 💡 **Proposer une amélioration :** [Soumettre une idée](https://github.com/Pili-Tools/pili-client-support/issues/new?template=feature_request.md)

---

## 👨‍💻 Auteur & Crédits

Pili Client est conçu et développé avec ❤️ par **Misael Arroyo** ([Pili Tools](https://github.com/Pili-Tools)).

---

## 📄 Licence

Pili Client est distribué en tant que logiciel propriétaire gratuit (Freeware) développé par **Misael Arroyo (Pili Tools)**. Voir [LICENSE](LICENSE).
