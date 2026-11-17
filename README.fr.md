<div align="center">
  <img src="assets/images/logo.svg" alt="Logo de Pili Client" width="128" height="128" />
  <h1>Pili Client</h1>
  <p><strong>Client HTTP/REST rapide, compatible Git et respectueux de la vie privée pour Visual Studio Code et ses dérivés.</strong></p>

  <p>
    <a href="README.md">English</a> •
    <a href="README.es.md">Español</a> •
    <a href="README.de.md">Deutsch</a> •
    <a href="README.fr.md"><strong>Français</strong></a> •
    <a href="README.pt.md">Português</a> •
    <a href="README.zh-CN.md">简体中文</a>
  </p>

  <p>
    <a href="https://marketplace.visualstudio.com/items?itemName=pili-client.pili-client"><img src="https://img.shields.io/badge/VS%20Marketplace-Pili%20Client-blue?logo=visual-studio-code" alt="Visual Studio Marketplace" /></a>
    <a href="https://open-vsx.org/extension/pili-client/pili-client"><img src="https://img.shields.io/badge/Open%20VSX-Pili%20Client-purple?logo=eclipseide" alt="Open VSX" /></a>
    <a href="https://github.com/Pili-Tools/pili-client-support/releases"><img src="https://img.shields.io/badge/Release-v0.1.0-green" alt="Dernière version" /></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/Licence-Freeware-informational" alt="Licence" /></a>
  </p>
</div>

---

## ⚡ Présentation

**Pili Client** est un client d'API REST moderne, rapide et conçu pour les développeurs, intégré à **VS Code**, **Cursor**, **VSCodium**, **Windsurf** et **Eclipse Theia**.

Toutes vos collections, environnements et requêtes sont stockés directement dans le dossier `.pili-client/` de votre projet, vous permettant de versionner vos tests avec Git sans dépendance à des services cloud propriétaires.

---

## ✨ Fonctionnalités Principales

* 🚀 **Compatible Git par conception :** Vos requêtes et environnements sont sauvegardés sous forme de fichiers JSON lisibles dans `.pili-client/`.
* 🔒 **Confidentialité totale et séparation des secrets :** Vos clés d'API et mots de passe sensibles résident dans `.pili-client/.secrets.json` (ignoré automatiquement par `.gitignore`).
* ⚡ **Interface réactive en Svelte :** Démarrage instantané et empreinte mémoire minimale dans l'éditeur.
* 🌐 **Sans restrictions CORS :** Les requêtes HTTP/HTTPS s'exécutent dans le processus Node.js natif.
* 🔄 **Synchronisation en direct :** Détection automatique des modifications de fichiers provoquées par Git (`pull`, `checkout`, `merge`).
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

## 💬 Communauté & Support

* 🐛 **Signaler un bug :** [Ouvrir un rapport](https://github.com/Pili-Tools/pili-client-support/issues/new?template=bug_report.md)
* 💡 **Proposer une amélioration :** [Soumettre une idée](https://github.com/Pili-Tools/pili-client-support/issues/new?template=feature_request.md)

---

## 📄 Licence

Pili Client est distribué en tant que logiciel propriétaire gratuit (Freeware). Voir [LICENSE](LICENSE).
