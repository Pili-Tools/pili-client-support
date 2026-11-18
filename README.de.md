<div align="center">
  <img src="assets/images/logo.svg" alt="Pili Client Logo" width="128" height="128" />
  <h1>Pili Client</h1>
  <p><strong>Schneller, Git-freundlicher und datenschutzorientierter HTTP/REST-Client für Visual Studio Code und Forks.</strong></p>
  <p>
    <em>Entwickelt mit ❤️ von <strong>Misael Arroyo</strong></em><br />
    <a href="https://ko-fi.com/piliclient"><img src="https://img.shields.io/badge/spendier%20mir%20einen%20kaffee-spenden-yellow" alt="Spenden" /></a>
  </p>

  <p>
    <a href="README.md">English</a> •
    <a href="README.es.md">Español</a> •
    <a href="README.de.md"><strong>Deutsch</strong></a> •
    <a href="README.fr.md">Français</a> •
    <a href="README.pt.md">Português</a> •
    <a href="README.zh-CN.md">简体中文</a>
  </p>

  <p>
    <a href="https://marketplace.visualstudio.com/items?itemName=PiliClient.pili-client"><img src="https://img.shields.io/badge/VS%20Marketplace-Pili%20Client-blue?logo=visual-studio-code" alt="Visual Studio Marketplace" /></a>
    <a href="https://open-vsx.org/extension/PiliClient/pili-client"><img src="https://img.shields.io/badge/Open%20VSX-Pili%20Client-purple?logo=eclipseide" alt="Open VSX" /></a>
    <a href="https://github.com/Pili-Tools/pili-client-support/releases"><img src="https://img.shields.io/badge/Release-v0.1.2-green" alt="Aktuelle Version" /></a>
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

## 🔮 Geplante Funktionen & Roadmap

Wir entwickeln **Pili Client** kontinuierlich weiter, um den schnellsten, saubersten und datenschutzfreundlichsten API-Client für deinen Editor bereitzustellen. Daran arbeiten wir als Nächstes:

* 🟡 **Pre-Request- & Test-Scripting-Engine (`pi.*` & `pm.*`):** Sichere, isolierte Ausführung von modernem JavaScript (`async/await`), Test-Assertionen und 100%ige Kompatibilität mit bestehenden Postman-Skripten.
* 🔵 **Reibungsloser Importer & Exporter:** Import und Export von Postman-Sammlungen (v2.1) inklusive Testskripten sowie Unterstützung für OpenAPI / Swagger-Spezifikationen.
* 🔵 **GraphQL-Unterstützung:** Interaktiver Query-/Mutation-Builder, Variablen-Editor und Schema-Introspektion.
* 🔵 **Echtzeit-Protokolle (WebSocket & SSE):** Live-Streaming-Nachrichten direkt in der Erweiterung senden und analysieren.
* 💡 **API-Dokumentationsgenerator:** Export von Sammlungen in ansprechende Markdown- oder interaktive HTML-Dokumentationen mit nur einem Klick.

> 💬 **Möchtest du, dass wir einer Funktion Priorität einräumen, oder hast du eine Idee?**  
> Lass es uns wissen und erstelle einen [Feature-Wunsch](https://github.com/Pili-Tools/pili-client-support/issues/new?template=feature_request.md)!

---

## 💬 Community & Support

* 🐛 **Fehler melden:** [Issue erstellen](https://github.com/Pili-Tools/pili-client-support/issues/new?template=bug_report.md)
* 💡 **Funktionswünsche:** [Vorschlag einreichen](https://github.com/Pili-Tools/pili-client-support/issues/new?template=feature_request.md)

---

## 👨‍💻 Autor & Credits

Pili Client wird mit ❤️ von **Misael Arroyo** ([Pili Tools](https://github.com/Pili-Tools)) entworfen und entwickelt.

---

## 📄 Lizenz

Pili Client wird als kostenlose proprietäre Software (Freeware) von **Misael Arroyo (Pili Tools)** bereitgestellt. Siehe [LICENSE](LICENSE).
