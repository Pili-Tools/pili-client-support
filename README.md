<div align="center">
  <img src="assets/images/logo.svg" alt="Pili Client Logo" width="128" height="128" />
  <h1>Pili Client</h1>
  <p><strong>Fast, Git-friendly, and privacy-first HTTP/REST client for Visual Studio Code and forks.</strong></p>

  <p>
    <a href="README.md">English</a> •
    <a href="README.es.md">Español</a> •
    <a href="README.de.md">Deutsch</a> •
    <a href="README.fr.md">Français</a> •
    <a href="README.pt.md">Português</a> •
    <a href="README.zh-CN.md">简体中文</a>
  </p>

  <p>
    <a href="https://marketplace.visualstudio.com/items?itemName=pili-client.pili-client"><img src="https://img.shields.io/badge/VS%20Marketplace-Pili%20Client-blue?logo=visual-studio-code" alt="Visual Studio Marketplace" /></a>
    <a href="https://open-vsx.org/extension/pili-client/pili-client"><img src="https://img.shields.io/badge/Open%20VSX-Pili%20Client-purple?logo=eclipseide" alt="Open VSX" /></a>
    <a href="https://github.com/Pili-Tools/pili-client-support/releases"><img src="https://img.shields.io/badge/Release-v0.1.0-green" alt="Latest Release" /></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-Freeware-informational" alt="License" /></a>
  </p>
</div>

---

## ⚡ Overview

**Pili Client** is a lightweight, modern, and developer-friendly REST API client seamlessly embedded into **VS Code**, **Cursor**, **VSCodium**, **Windsurf**, and **Eclipse Theia**.

Unlike traditional API clients that store your requests in proprietary cloud accounts, Pili Client keeps all collections, environments, and tests directly in your workspace repository under `.pili-client/`. Track your endpoints, commit them with Git, review changes in pull requests, and collaborate with your team with zero lock-in.

---

## ✨ Key Features

* 🚀 **Git-Friendly by Design:** Collections, requests, and environments are saved as clean JSON files inside `.pili-client/`. Version them alongside your application code.
* 🔒 **Zero Cloud Leak & Secret Isolation:** Your sensitive API tokens, passwords, and private keys reside in `.pili-client/.secrets.json`—automatically excluded by `.gitignore`.
* ⚡ **High-Performance Svelte UI:** Near-instant boot time, fluid reactivity, and minimal memory footprint inside your editor.
* 🌐 **No CORS Limitations:** HTTP/HTTPS requests run through the extension host process in native Node.js.
* 🔄 **Live Workspace Sync:** Automatic filesystem watcher detects external Git changes (`checkout`, `pull`, `merge`) and instantly updates the collection tree.
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

1. Open any project workspace in VS Code or your favorite fork.
2. Click on the **Pili Client** icon in the Activity Bar (left sidebar).
3. Click **New Request** (`+`) or run the command palette (`Ctrl+Shift+P` / `Cmd+Shift+P`):
   ```
   Pili Client: Open HTTP Client
   ```
4. Enter your URL, choose an HTTP method (`GET`, `POST`, `PUT`, `DELETE`), configure headers/body, and hit **Send** (`Ctrl+Enter` / `Cmd+Enter`).

---

## 📁 Repository Structure in Your Projects

When you save requests or environments, Pili Client automatically creates the following folder in your project root:

```text
my-project/
├── .pili-client/
│   ├── environments/         # Shared environments (.env, JSON)
│   ├── .secrets.json         # Sensitive values (never committed)
│   ├── _settings.json        # Collection-wide headers, auth & pre-scripts
│   └── User_Service/
│       ├── Get_Users.pili.json
│       └── Create_User.pili.json
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

## 📄 License

Pili Client is distributed as free-to-use proprietary software (Freeware). For full terms and conditions, see [LICENSE](LICENSE).
