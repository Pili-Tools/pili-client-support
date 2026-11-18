<div align="center">
  <img src="assets/images/logo.svg" alt="Logotipo do Pili Client" width="128" height="128" />
  <h1>Pili Client</h1>
  <p><strong>Cliente HTTP/REST rápido, amigável ao Git e focado em privacidade para Visual Studio Code e forks.</strong></p>
  <p><em>Desenvolvido com ❤️ por <strong>Misael Arroyo</strong></em></p>

  <p>
    <a href="README.md">English</a> •
    <a href="README.es.md">Español</a> •
    <a href="README.de.md">Deutsch</a> •
    <a href="README.fr.md">Français</a> •
    <a href="README.pt.md"><strong>Português</strong></a> •
    <a href="README.zh-CN.md">简体中文</a>
  </p>

  <p>
    <a href="https://marketplace.visualstudio.com/items?itemName=PiliClient.pili-client"><img src="https://img.shields.io/badge/VS%20Marketplace-Pili%20Client-blue?logo=visual-studio-code" alt="Visual Studio Marketplace" /></a>
    <a href="https://open-vsx.org/extension/PiliClient/pili-client"><img src="https://img.shields.io/badge/Open%20VSX-Pili%20Client-purple?logo=eclipseide" alt="Open VSX" /></a>
    <a href="https://github.com/Pili-Tools/pili-client-support/releases"><img src="https://img.shields.io/badge/Release-v0.1.1-green" alt="Versão mais recente" /></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/Licen%C3%A7a-Freeware-informational" alt="Licença" /></a>
  </p>
</div>

---

## ⚡ Visão Geral

**Pili Client** é um cliente REST moderno, rápido e feito para desenvolvedores, totalmente integrado ao **VS Code**, **Cursor**, **VSCodium**, **Windsurf** e **Eclipse Theia**.

Ao contrário de clientes de API tradicionais que armazenam seus dados em nuvens proprietárias, o Pili Client mantém todas as suas coleções, ambientes, cookies e testes salvos de forma segura no armazenamento global de extensões do seu editor em sua própria máquina. Isso mantém seus dados independentes do projeto ou pasta aberta e seus repositórios Git sempre limpos.

---

## ✨ Recursos Principais

* 🚀 **Independente do Workspace & Repositórios Limpos:** Requisições e ambientes são armazenados no armazenamento global local do seu editor, sem poluir seus repositórios Git.
* 🔒 **Privacidade total e separação de segredos:** 100% local e offline. Senhas e tokens confidenciais residem de forma segura na sua máquina.
* ⚡ **Interface ágil em Svelte:** Inicialização rápida, reatividade fluida e baixo consumo de memória.
* 🌐 **Sem bloqueios de CORS:** As requisições são resolvidas diretamente no processo Node.js nativo.
* 🔄 **Sincronização em tempo real:** Observador do sistema de arquivos atualiza a árvore lateral automaticamente.
* 🧪 **Executor de Coleções (Collection Runner):** Execuções em lote, testes baseados em dados (CSV/JSON), asserções automáticas e relatórios (HTML, JUnit).
* 🍪 **Gerenciador de Cookies e Certificados:** Controle dedicado para cookies e certificados mTLS de cliente (PFX, PEM, CRT, KEY).
* 💻 **Gerador de Código e Tipos:** Criação de snippets de código (cURL, Python, PHP, Axios, etc.) e interfaces TypeScript automáticas a partir de respostas JSON.
* 🌍 **Suporte a múltiplos idiomas:** Português, Inglês, Espanhol, Alemão, Francês e Chinês Simplificado.

---

## 📦 Instalação

### Via VS Code / Cursor / Windsurf
1. Abra a aba de Extensões (`Ctrl+Shift+X` ou `Cmd+Shift+X`).
2. Pesquise por `Pili Client`.
3. Clique em **Instalar**.

### Via VSCodium / Open VSX
1. Abra o gerenciador de extensões do Open VSX.
2. Pesquise por `Pili Client` e instale.

---

## 📁 Localização dos Arquivos e Armazenamento

Por padrão, o Pili Client armazena suas coleções, requisições, ambientes, cookies e certificados no diretório oficial de armazenamento global do VS Code:

* **Windows:** `%APPDATA%\Code\User\globalStorage\PiliClient.pili-client`
* **macOS:** `~/Library/Application Support/Code/User/globalStorage/PiliClient.pili-client`
* **Linux:** `~/.config/Code/User/globalStorage/PiliClient.pili-client`
* **VS Code Server (Linux / Remoto):** `~/.vscode-server/data/User/globalStorage/PiliClient.pili-client`

---

## 💬 Comunidade & Suporte

* 🐛 **Reportar um Erro:** [Abrir chamado](https://github.com/Pili-Tools/pili-client-support/issues/new?template=bug_report.md)
* 💡 **Sugerir Funcionalidades:** [Enviar sugestão](https://github.com/Pili-Tools/pili-client-support/issues/new?template=feature_request.md)

---

## 👨‍💻 Autor & Créditos

O Pili Client foi criado e desenvolvido com ❤️ por **Misael Arroyo** ([Pili Tools](https://github.com/Pili-Tools)).

---

## 📄 Licença

O Pili Client é distribuído como software proprietário gratuito (Freeware) desenvolvido por **Misael Arroyo (Pili Tools)**. Consulte [LICENSE](LICENSE).
