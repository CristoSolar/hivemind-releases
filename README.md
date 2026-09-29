# HiveMind — descargas

Instaladores de [HiveMind](https://hivemindai.cl): un equipo de agentes de IA con nombre, en tu escritorio.
Este repositorio solo publica las versiones; el código vive en un repositorio privado.

## Instalar

**Windows 11:** [HiveMind-Setup.exe](https://github.com/CristoSolar/hivemind-releases/releases/latest/download/HiveMind-Setup.exe)
(instalación por usuario, sin administrador; SHA-256 junto al archivo en cada versión).

**Linux y macOS** (macOS en beta, necesita [Homebrew](https://brew.sh)):

```bash
curl -fsSL https://hivemindai.cl/install.sh | bash
```

Repetirlo actualiza. Para desinstalar sin perder tus agentes ni chats:

```bash
curl -fsSL https://hivemindai.cl/install.sh | bash -s -- --uninstall
```

Requiere [Claude Code](https://claude.com/claude-code) con sesión iniciada, o un proveedor configurado.

Todas las versiones: [Releases](https://github.com/CristoSolar/hivemind-releases/releases).
