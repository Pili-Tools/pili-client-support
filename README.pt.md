<div align="center">
  <img src="assets/images/logo.svg" alt="Logotipo do Pili Client" width="128" height="128" />
  <h1>Pili Client</h1>
  <p><strong>Cliente HTTP/REST rápido, amigável ao Git e focado em privacidade para Visual Studio Code e forks.</strong></p>

  <p>
    <a href="README.md">English</a> •
    <a href="README.es.md">Español</a> •
    <a href="README.de.md">Deutsch</a> •
    <a href="README.fr.md">Français</a> •
    <a href="README.pt.md"><strong>Português</strong></a> •
    <a href="README.zh-CN.md">简体中文</a>
  </p>

  <p>
    <a href="https://marketplace.visualstudio.com/items?itemName=pili-client.pili-client"><img src="https://img.shields.io/badge/VS%20Marketplace-Pili%20Client-blue?logo=visual-studio-code" alt="Visual Studio Marketplace" /></a>
    <a href="https://open-vsx.org/extension/pili-client/pili-client"><img src="https://img.shields.io/badge/Open%20VSX-Pili%20Client-purple?logo=eclipseide" alt="Open VSX" /></a>
    <a href="https://github.com/Pili-Tools/pili-client-support/releases"><img src="https://img.shields.io/badge/Release-v0.1.1-green" alt="Versão mais recente" /></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/Licen%C3%A7a-Freeware-informational" alt="Licença" /></a>
  </p>
</div>

---

## ⚡ Visão Geral

**Pili Client** é um cliente REST moderno, rápido e feito para desenvolvedores, totalmente integrado ao **VS Code**, **Cursor**, **VSCodium**, **Windsurf** e **Eclipse Theia**.

Suas requisições, coleções e variáveis de ambiente são salvas diretamente no repositório do seu projeto na pasta `.pili-client/`, permitindo versioná-las no Git sem depender de serviços em nuvem proprietários.

---

## ✨ Recursos Principais

* 🚀 **Amigável ao Git:** Requisições e ambientes são armazenados como arquivos JSON limpos na pasta `.pili-client/`.
* 🔒 **Privacidade total e separação de segredos:** Senhas e tokens confidenciais ficam em `.pili-client/.secrets.json` (ignorado automaticamente pelo `.gitignore`).
* ⚡ **Interface ágil em Svelte:** Inicialização rápida, reatividade fluida e baixo consumo de memória.
* 🌐 **Sem bloqueios de CORS:** As requisições são resolvidas diretamente no processo Node.js nativo.
* 🔄 **Sincronização em tempo real:** Observador do sistema de arquivos atualiza a árvore lateral automaticamente em operações Git (`pull`, `checkout`, `merge`).
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

## 💬 Comunidade & Suporte

* 🐛 **Reportar um Erro:** [Abrir chamado](https://github.com/Pili-Tools/pili-client-support/issues/new?template=bug_report.md)
* 💡 **Sugerir Funcionalidades:** [Enviar sugestão](https://github.com/Pili-Tools/pili-client-support/issues/new?template=feature_request.md)

---

## 📄 Licença

O Pili Client é distribuído como software proprietário gratuito (Freeware). Consulte [LICENSE](LICENSE).
