<div align="center">
  <img src="assets/images/logo.svg" alt="Pili Client Logo" width="128" height="128" />
  <h1>Pili Client</h1>
  <p><strong>Schneller, Git-freundlicher und datenschutzorientierter HTTP/REST-Client für Visual Studio Code und Forks.</strong></p>

  <p>
    <a href="README.md">English</a> •
    <a href="README.es.md">Español</a> •
    <a href="README.de.md"><strong>Deutsch</strong></a> •
    <a href="README.fr.md">Français</a> •
    <a href="README.pt.md">Português</a> •
    <a href="README.zh-CN.md">简体中文</a>
  </p>

  <p>
    <a href="https://marketplace.visualstudio.com/items?itemName=pili-client.pili-client"><img src="https://img.shields.io/badge/VS%20Marketplace-Pili%20Client-blue?logo=visual-studio-code" alt="Visual Studio Marketplace" /></a>
    <a href="https://open-vsx.org/extension/pili-client/pili-client"><img src="https://img.shields.io/badge/Open%20VSX-Pili%20Client-purple?logo=eclipseide" alt="Open VSX" /></a>
    <a href="https://github.com/Pili-Tools/pili-client-support/releases"><img src="https://img.shields.io/badge/Release-v0.1.1-green" alt="Aktuelle Version" /></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/Lizenz-Freeware-informational" alt="Lizenz" /></a>
  </p>
</div>

---

## ⚡ Übersicht

**Pili Client** ist ein leichtgewichtiger, moderner REST-API-Client für Entwickler, der direkt in **VS Code**, **Cursor**, **VSCodium**, **Windsurf** und **Eclipse Theia** integriert ist.

Im Gegensatz zu herkömmlichen API-Clients, die Anfragen in proprietären Cloud-Diensten speichern, speichert Pili Client alle Sammlungen, Umgebungen, Cookies und Tests sicher im globalen Erweiterungsspeicher Ihres Editors auf Ihrem lokalen Rechner. Dadurch bleiben Ihre Daten unabhängig von geöffneten Projekten oder Workspaces und Ihre Git-Repositories sauber.

---

## ✨ Hauptfunktionen

* 🚀 **Unabhängig vom Arbeitsbereich & Saubere Repositories:** Anfragen und Umgebungen werden im lokalen globalen Speicher Ihres Editors abgelegt. Kein Durcheinander in Ihren Code-Repositories.
* 🔒 **Datenschutz & Geheimnis-Trennung:** 100% lokal und offline. Sensible API-Schlüssel, Passwörter und Tokens liegen sicher auf Ihrem Rechner.
* ⚡ **Schnelle Svelte-Oberfläche:** Sofortiger Start, flüssige Reaktivität und minimaler Speicherverbrauch.
* 🌐 **Keine CORS-Beschränkungen:** Anfragen laufen über den nativen Node.js-Prozess des Editors.
* 🔄 **Echtzeit-Synchronisierung:** Dateisystem-Watcher erkennt externe Änderungen automatisch.
* 🧪 **Automatisierter Collection Runner:** Sequenzielle Ausführung, datengesteuerte Tests mit CSV/JSON und Berichterstellung (HTML, JUnit).
* 🍪 **Cookie- & Zertifikats-Manager:** Vollständige Verwaltung von Sitzungs-Cookies und mTLS-Client-Zertifikaten (PFX, PEM, CRT, KEY).
* 💻 **Code- und Typengenerierung:** Automatische Generierung von Code-Snippets (cURL, Fetch, Python, PHP usw.) und TypeScript-Schnittstellen.
* 🌍 **Mehrsprachig:** Verfügbar in Deutsch, Englisch, Spanisch, Französisch, Portugiesisch und Chinesisch.

---

## 📦 Installation

### Über VS Code / Cursor / Windsurf
1. Erweiterungs-Ansicht öffnen (`Ctrl+Shift+X` bzw. `Cmd+Shift+X`).
2. Nach `Pili Client` suchen.
3. Auf **Installieren** klicken.

### Über VSCodium / Open VSX
1. Open VSX Erweiterungsmanager öffnen.
2. Nach `Pili Client` suchen und **Installieren** wählen.

---

## 📁 Speicherorte der Dateien

Standardmäßig speichert Pili Client alle Sammlungen, Anfragen, Umgebungen, Cookies und Zertifikate im offiziellen globalen VS Code-Speicherverzeichnis:

* **Windows:** `%APPDATA%\Code\User\globalStorage\PiliClient.pili-client`
* **macOS:** `~/Library/Application Support/Code/User/globalStorage/PiliClient.pili-client`
* **Linux:** `~/.config/Code/User/globalStorage/PiliClient.pili-client`
* **VS Code Server (Linux / Remote):** `~/.vscode-server/data/User/globalStorage/PiliClient.pili-client`

---

## 💬 Community & Support

* 🐛 **Fehler melden:** [Issue erstellen](https://github.com/Pili-Tools/pili-client-support/issues/new?template=bug_report.md)
* 💡 **Funktionswünsche:** [Vorschlag einreichen](https://github.com/Pili-Tools/pili-client-support/issues/new?template=feature_request.md)

---

## 📄 Lizenz

Pili Client wird als kostenlose proprietäre Software (Freeware) bereitgestellt. Siehe [LICENSE](LICENSE).
