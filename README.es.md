<div align="center">
  <img src="assets/images/logo.svg" alt="Logo de Pili Client" width="128" height="128" />
  <h1>Pili Client</h1>
  <p><strong>Cliente HTTP/REST rápido, amigable con Git y respetuoso de la privacidad para Visual Studio Code y forks.</strong></p>

  <p>
    <a href="README.md">English</a> •
    <a href="README.es.md"><strong>Español</strong></a> •
    <a href="README.de.md">Deutsch</a> •
    <a href="README.fr.md">Français</a> •
    <a href="README.pt.md">Português</a> •
    <a href="README.zh-CN.md">简体中文</a>
  </p>

  <p>
    <a href="https://marketplace.visualstudio.com/items?itemName=pili-client.pili-client"><img src="https://img.shields.io/badge/VS%20Marketplace-Pili%20Client-blue?logo=visual-studio-code" alt="Visual Studio Marketplace" /></a>
    <a href="https://open-vsx.org/extension/pili-client/pili-client"><img src="https://img.shields.io/badge/Open%20VSX-Pili%20Client-purple?logo=eclipseide" alt="Open VSX" /></a>
    <a href="https://github.com/Pili-Tools/pili-client-support/releases"><img src="https://img.shields.io/badge/Release-v0.1.0-green" alt="Última versión" /></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/Licencia-Freeware-informational" alt="Licencia" /></a>
  </p>
</div>

---

## ⚡ Visión General

**Pili Client** es un cliente de APIs REST ligero, moderno y pensado para desarrolladores, integrado directamente en **VS Code**, **Cursor**, **VSCodium**, **Windsurf** y **Eclipse Theia**.

A diferencia de los clientes de APIs tradicionales que almacenan tus peticiones en cuentas propietarias en la nube, Pili Client guarda todas las colecciones, entornos y pruebas directamente en el repositorio de tu proyecto bajo `.pili-client/`. Rastrea tus endpoints, haz commits con Git, revisa cambios en pull requests y colabora con tu equipo sin ataduras de proveedores.

---

## ✨ Características Principales

* 🚀 **Amigable con Git por diseño:** Peticiones, colecciones y entornos se guardan como archivos JSON limpios dentro de `.pili-client/` para versionarlos con tu código.
* 🔒 **Cero fugas a la nube y separación de secretos:** Tus tokens, contraseñas y claves privadas residen en `.pili-client/.secrets.json` (excluido automáticamente por `.gitignore`).
* ⚡ **Interfaz fluida en Svelte:** Arranque casi instantáneo, reactividad total y mínimo consumo de memoria en tu editor.
* 🌐 **Sin restricciones de CORS:** Las peticiones HTTP/HTTPS se ejecutan en el proceso nativo de Node.js del Extension Host.
* 🔄 **Sincronización en vivo del espacio de trabajo:** Observador de sistema de archivos que detecta cambios externos de Git (`checkout`, `pull`, `merge`) y actualiza el árbol automáticamente.
* 🧪 **Collection Runner automatizado:** Ejecuta secuencias de peticiones, pruebas basadas en datos con archivos CSV/JSON, aserciones automáticas y reportes en HTML o JUnit.
* 🍪 **Gestor de Cookies y Certificados:** Panel dedicado para la gestión de cookies de sesión y certificados de cliente mTLS (PFX, PEM, CRT, KEY).
* 💻 **Generador de Código y Tipos:** Genera snippets en múltiples lenguajes (cURL, Fetch, Python, PHP, Axios, etc.) e interfaces de TypeScript automáticas a partir de las respuestas JSON.
* 🌍 **Soporte Multilingüe Nativo:** Disponible en Español, Inglés, Alemán, Francés, Portugués y Chino Simplificado.

---

## 📦 Instalación

### Desde VS Code / Cursor / Windsurf
1. Abre la vista de Extensiones (`Ctrl+Shift+X` o `Cmd+Shift+X`).
2. Busca `Pili Client`.
3. Haz clic en **Instalar**.

### Desde VSCodium / Open VSX
1. Abre el gestor de extensiones.
2. Busca `Pili Client` desde el registro de Open VSX.
3. Haz clic en **Instalar**.

### Instalación Manual (.VSIX)
1. Descarga el paquete `.vsix` más reciente desde [Releases](https://github.com/Pili-Tools/pili-client-support/releases).
2. Ejecuta en tu terminal:
   ```bash
   code --install-extension pili-client-0.1.0.vsix
   ```
   *(O arrastra el archivo `.vsix` hacia la vista de Extensiones de tu editor).*

---

## 🚀 Inicio Rápido

1. Abre cualquier carpeta o proyecto en VS Code o tu editor favorito.
2. Haz clic en el icono de **Pili Client** en la Barra de Actividad (barra lateral izquierda).
3. Haz clic en **Nueva Petición** (`+`) o abre la paleta de comandos (`Ctrl+Shift+P` / `Cmd+Shift+P`):
   ```
   Pili Client: Abrir Cliente HTTP
   ```
4. Escribe la URL, selecciona el método HTTP (`GET`, `POST`, `PUT`, `DELETE`), configura cabeceras o cuerpo y presiona **Enviar** (`Ctrl+Enter` / `Cmd+Enter`).

---

## 📁 Estructura en tus Proyectos

Cuando guardas peticiones o entornos, Pili Client genera la siguiente estructura en la raíz de tu proyecto:

```text
mi-proyecto/
├── .pili-client/
│   ├── environments/         # Entornos compartidos (.env, JSON)
│   ├── .secrets.json         # Valores sensibles (nunca en el commit)
│   ├── _settings.json        # Ajustes globales de colección (headers, scripts)
│   └── Servicio_Usuarios/
│       ├── Obtener_Usuarios.pili.json
│       └── Crear_Usuario.pili.json
```

---

## 💬 Comunidad y Soporte

Este repositorio (`Pili-Tools/pili-client-support`) es el canal oficial para soporte al usuario, feedback y seguimiento de problemas.

* 🐛 **Reportar un Error:** ¿Encontraste un problema? [Abre un Reporte de Error](https://github.com/Pili-Tools/pili-client-support/issues/new?template=bug_report.md).
* 💡 **Solicitar Funcionalidades:** ¿Tienes una sugerencia de mejora? [Envía una Solicitud](https://github.com/Pili-Tools/pili-client-support/issues/new?template=feature_request.md).
* 📢 **Novedades y Versiones:** Sigue este repositorio para recibir notificaciones sobre nuevas versiones y actualizaciones.

---

## ☕ Soporte y Donaciones

Pili Client es completamente gratuito tanto para uso personal como educativo y comercial.

Si Pili Client te resulta útil y agiliza tu desarrollo diario de APIs, puedes apoyar su mantenimiento continuo:

* ☕ **Buy Me a Coffee / Ko-fi:** *(Enlace disponible próximamente)*
* ⭐ **Dale una estrella a este repositorio** para dar a conocer Pili Client a otros desarrolladores.

---

## 📄 Licencia

Pili Client se distribuye bajo una licencia de software propietario gratuito (Freeware). Para consultar los términos completos, consulta [LICENSE](LICENSE).
