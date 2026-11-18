<div align="center">
  <img src="assets/images/logo.svg" alt="Pili Client 图标" width="128" height="128" />
  <h1>Pili Client</h1>
  <p><strong>专为 Visual Studio Code 及衍生编辑器打造的快速、Git 友好且注重隐私的 HTTP/REST 客户端。</strong></p>
  <p>
    <em>由 <strong>Misael Arroyo</strong> 用 ❤️ 开发</em><br />
    <a href="https://ko-fi.com/piliclient"><img src="https://img.shields.io/badge/%E8%AF%B7%E6%88%91%E5%96%9D%E6%9D%AF%E5%92%96%E5%95%A1-%E8%B5%9E%E5%8A%A9-yellow" alt="赞助" /></a>
  </p>

  <p>
    <a href="README.md">English</a> •
    <a href="README.es.md">Español</a> •
    <a href="README.de.md">Deutsch</a> •
    <a href="README.fr.md">Français</a> •
    <a href="README.pt.md">Português</a> •
    <a href="README.zh-CN.md"><strong>简体中文</strong></a>
  </p>

  <p>
    <a href="https://marketplace.visualstudio.com/items?itemName=PiliClient.pili-client"><img src="https://img.shields.io/badge/VS%20Marketplace-Pili%20Client-blue?logo=visual-studio-code" alt="Visual Studio Marketplace" /></a>
    <a href="https://open-vsx.org/extension/PiliClient/pili-client"><img src="https://img.shields.io/badge/Open%20VSX-Pili%20Client-purple?logo=eclipseide" alt="Open VSX" /></a>
    <a href="https://github.com/Pili-Tools/pili-client-support/releases"><img src="https://img.shields.io/badge/Release-v0.1.1-green" alt="最新版本" /></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/许可-免费专有软件-informational" alt="许可证" /></a>
  </p>
</div>

---

## ⚡ 概述

**Pili Client** 是一款轻量、现代且专为开发者设计的 REST API 客户端，深度集成于 **VS Code**、**Cursor**、**VSCodium**、**Windsurf** 和 **Eclipse Theia**。

不同于将您的请求数据存储在专有云端的传统 API 工具，Pili Client 将所有集合、环境变量、Cookie 和测试数据安全保存在您本地编辑器的全局扩展存储中。无论您打开什么项目或工作区，您的 API 数据都随时可用，同时保持您的 Git 代码仓库干净整洁。

---

## ✨ 核心特性

* 🚀 **独立于工作区与保持仓库干净：** 请求与环境配置均保存于编辑器的本地全局存储目录中，不会污染您的代码仓库。
* 🔒 **隐私优先与敏感凭证隔离：** 100% 本地离线存储。密码、API Key 等敏感数据存放于本地，无外部云同步泄漏风险。
* ⚡ **极速 Svelte 界面：** 秒级启动，流畅响应，超低内存占用。
* 🌐 **无 CORS 跨域限制：** 请求通过编辑器后台 Node.js 原生进程直接发送。
* 🔄 **实时存储同步：** 文件监听器可自动识别外部变更并即时刷新集合列表。
* 🧪 **自动化集合执行器（Collection Runner）：** 支持批量运行、基于 CSV/JSON 数据的驱动测试、自动断言以及 HTML/JUnit 格式报告导出。
* 🍪 **Cookie 与证书管理器：** 专属面板管理会话 Cookie 与 mTLS 双向认证证书（PFX、PEM、CRT、KEY）。
* 💻 **代码与类型生成：** 一键生成多种语言请求代码（cURL、Python、PHP、Fetch、Axios 等）并可从 JSON 响应中自动生成 TypeScript 接口。
* 🌍 **多语言原生支持：** 支持简体中文、英语、西班牙语、德语、法语及葡萄牙语。

---

## 📦 安装方式

### 在 VS Code / Cursor / Windsurf 中安装
1. 打开扩展面板（快捷键 `Ctrl+Shift+X` 或 `Cmd+Shift+X`）。
2. 搜索 `Pili Client`。
3. 点击 **安装**。

### 在 VSCodium / Open VSX 中安装
1. 打开 Open VSX 插件市场。
2. 搜索 `Pili Client` 并点击安装。

---

## 📁 文件与数据存储位置

默认情况下，Pili Client 将您的所有集合、请求、环境、Cookie 和证书保存在 VS Code 官方全局扩展存储目录中：

* **Windows:** `%APPDATA%\Code\User\globalStorage\PiliClient.pili-client`
* **macOS:** `~/Library/Application Support/Code/User/globalStorage/PiliClient.pili-client`
* **Linux:** `~/.config/Code/User/globalStorage/PiliClient.pili-client`
* **VS Code Server (Linux / 远程):** `~/.vscode-server/data/User/globalStorage/PiliClient.pili-client`

---

## 🔮 未来规划与路线图 (Roadmap)

我们一直在持续优化 **Pili Client**，致力于为您的编辑器打造最快速、整洁且注重隐私的 API 调试工具。以下是我们近期重点推进的新特性：

* 🟡 **Pre-Request 与测试脚本引擎 (`pi.*` & `pm.*`)：** 在隔离沙箱中安全执行现代 JavaScript (`async/await`)、断言测试以及 100% 兼容现有的 Postman 脚本。
* 🔵 **无缝导入与导出：** 支持完整保留测试脚本的 Postman (v2.1) 集合导入导出，并支持 OpenAPI / Swagger 规范。
* 🔵 **GraphQL 支持：** 交互式查询/变更构建器、变量编辑器与 Schema 自省。
* 🔵 **实时协议支持 (WebSocket & SSE)：** 直接在扩展内进行实时流式消息的收发与检查。
* 💡 **API 文档生成器：** 一键将集合导出为整洁的 Markdown 或交互式 HTML 文档。

> 💬 **希望我们优先实现某项功能，或者有新想法？**  
> 欢迎通过提交 [功能建议 (Feature Request)](https://github.com/Pili-Tools/pili-client-support/issues/new?template=feature_request.md) 告诉我们！

---

## 💬 社区与技术支持

本仓库（`Pili-Tools/pili-client-support`）为官方公开支持与反馈渠道：

* 🐛 **报告缺陷：** [提交 Bug](https://github.com/Pili-Tools/pili-client-support/issues/new?template=bug_report.md)
* 💡 **需求建议：** [提出功能建议](https://github.com/Pili-Tools/pili-client-support/issues/new?template=feature_request.md)

---

## 👨‍💻 作者与致谢

Pili Client 由 **Misael Arroyo** ([Pili Tools](https://github.com/Pili-Tools)) 倾心设计与开发。

---

## 📄 许可证

Pili Client 作为由 **Misael Arroyo (Pili Tools)** 开发的免费专有软件（Freeware）分发。详见 [LICENSE](LICENSE)。
