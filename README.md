<div align="center">
  <img src="assets/images/logo.svg" alt="Pili Client Logo" width="128" height="128" />
  <h1>Pili Client</h1>
  <p><strong>Fast, Git-friendly, and privacy-first HTTP/REST client for Visual Studio Code and forks.</strong></p>
  <p><em>Developed with ❤️ by <strong>Misael Arroyo</strong></em></p>

  <p>
    <a href="README.md">English</a> •
    <a href="README.es.md">Español</a> •
    <a href="README.de.md">Deutsch</a> •
    <a href="README.fr.md">Français</a> •
    <a href="README.pt.md">Português</a> •
    <a href="README.zh-CN.md">简体中文</a>
  </p>

  <p>
    <a href="https://marketplace.visualstudio.com/items?itemName=PiliClient.pili-client"><img src="https://img.shields.io/badge/VS%20Marketplace-Pili%20Client-blue?logo=visual-studio-code" alt="Visual Studio Marketplace" /></a>
    <a href="https://open-vsx.org/extension/PiliClient/pili-client"><img src="https://img.shields.io/badge/Open%20VSX-Pili%20Client-purple?logo=eclipseide" alt="Open VSX" /></a>
    <a href="https://github.com/Pili-Tools/pili-client-support/releases"><img src="https://img.shields.io/badge/Release-v0.1.1-green" alt="Latest Release" /></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-Freeware-informational" alt="License" /></a>
  </p>
</div>

---

## ⚡ Overview

**Pili Client** is a lightweight, modern, and developer-friendly REST API client seamlessly embedded into **VS Code**, **Cursor**, **VSCodium**, **Windsurf**, and **Eclipse Theia**.

Unlike traditional API clients that store your requests in proprietary cloud accounts, Pili Client keeps all collections, environments, cookies, and tests securely stored on your local machine in your editor's global extension storage. This keeps your data completely independent of whatever folder, workspace, or project you have open in your editor, prevents repository clutter, and ensures zero cloud leak.

---

## ✨ Key Features

* 🚀 **Workspace-Independent & Git-Clean:** Collections, requests, and environments are saved in your editor's local global storage. Open any project, switch branches, or use an empty window—your API requests are always accessible without cluttering your code repositories.
* 🔒 **Zero Cloud Leak & Secret Isolation:** 100% offline and privacy-first. Your sensitive API tokens, passwords, and private keys reside safely on your machine without external cloud sync or vendor lock-in.
* ⚡ **High-Performance Svelte UI:** Near-instant boot time, fluid reactivity, and minimal memory footprint inside your editor.
* 🌐 **No CORS Limitations:** HTTP/HTTPS requests run through the extension host process in native Node.js.
* 🔄 **Live Storage Sync:** Automatic filesystem watcher detects external changes and instantly updates the collection tree.
* 🧪 **Automated Collection Runner:** Run request sequences, execute data-driven tests with CSV/JSON files, assert status/headers/body, and export test reports (HTML, JUnit).
* 🍪 **Cookie & Certificate Manager:** Dedicated management for session cookies and client mTLS certificates (PFX, PEM, CRT, KEY).
* 💻 **Code & Type Generator:** Generate client code snippets (cURL, Fetch, Python, PHP, Axios, etc.) and auto-generate TypeScript interfaces from JSON response payloads.
* 🌍 **Native Multilingual Support:** Available in English, Spanish, German, French, Portuguese, and Simplified Chinese.

---

## 📦 Installation

### From VS Code / Cursor / Windsurf
1. Open the Extensions view (`Ctrl+Shift+X` or `Cmd+Shift+X`).
2. Search for `Pili Client`.
3. Click **Install**.

### From VSCodium / Open VSX
1. Open your extension manager.
2. Search for `Pili Client` from the Open VSX registry.
3. Click **Install**.

### Manual VSIX Installation
1. Download the latest `.vsix` from [Releases](https://github.com/Pili-Tools/pili-client-support/releases).
2. Run in terminal:
   ```bash
   code --install-extension pili-client-0.1.0.vsix
   ```
   *(Or drag the `.vsix` file into your editor's Extensions view).*

---

## 🚀 Quick Start

1. Open any project workspace (or an empty window) in VS Code or your favorite fork.
2. Click on the **Pili Client** icon in the Activity Bar (left sidebar).
3. Click **New Request** (`+`) or run the command palette (`Ctrl+Shift+P` / `Cmd+Shift+P`):
   ```
   Pili Client: Open HTTP Client
   ```
4. Enter your URL, choose an HTTP method (`GET`, `POST`, `PUT`, `DELETE`), configure headers/body, and hit **Send** (`Ctrl+Enter` / `Cmd+Enter`).

---

## 📁 File & Data Storage Locations

By default, Pili Client stores your collections, requests, environments, cookies, and certificates in the official VS Code global storage directory:

* **Windows:** `%APPDATA%\Code\User\globalStorage\PiliClient.pili-client`
* **macOS:** `~/Library/Application Support/Code/User/globalStorage/PiliClient.pili-client`
* **Linux:** `~/.config/Code/User/globalStorage/PiliClient.pili-client`
* **VS Code Server (Linux / Remote):** `~/.vscode-server/data/User/globalStorage/PiliClient.pili-client`

> **Note:** If you are using editor forks such as **Cursor**, **VSCodium**, or **Windsurf**, the path automatically replaces `Code` with `Cursor`, `VSCodium`, etc.

### Internal Folder Structure

```text
PiliClient.pili-client/
├── environments/         # Shared environments (global.env.json, .env, JSON)
├── .secrets.json         # Sensitive values and local tokens (never exposed)
├── .cookies.json         # Persistent Cookie Jar
├── .certificates.json    # SSL/mTLS certificates configuration
└── [Collection_Name]/    # Your collections and folders
    ├── _collection.json  # Collection-wide headers, auth & pre-scripts
    ├── Get_Users.pili.json
    └── Create_User.pili.json
```

---

## 💬 Community & Support

This repository (`Pili-Tools/pili-client-support`) is the official public hub for user support, feedback, and issue tracking.

* 🐛 **Report a Bug:** Found an issue? [Open a Bug Report](https://github.com/Pili-Tools/pili-client-support/issues/new?template=bug_report.md).
* 💡 **Feature Requests:** Have an idea to improve Pili Client? [Submit a Feature Request](https://github.com/Pili-Tools/pili-client-support/issues/new?template=feature_request.md).
* 📢 **Announcements & Releases:** Watch this repository to stay informed about new releases and updates.

---

## ☕ Support & Donations

Pili Client is completely free to use for personal, educational, and commercial purposes.

If Pili Client saves you time and makes your API development smoother, you can support its ongoing development:

* ☕ **Buy Me a Coffee / Ko-fi:** *(Link coming soon)*
* ⭐ **Star this repository** to help other developers discover Pili Client!

---

## 👨‍💻 Author & Credits

Pili Client is designed and developed with ❤️ by **Misael Arroyo** ([Pili Tools](https://github.com/Pili-Tools)).

---

## 📄 License

Pili Client is distributed as free-to-use proprietary software (Freeware) developed by **Misael Arroyo (Pili Tools)**. For full terms and conditions, see [LICENSE](LICENSE).
