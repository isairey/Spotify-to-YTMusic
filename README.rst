<div align="center">

<img width="220" src="https://upload.wikimedia.org/wikipedia/commons/6/6a/Youtube_Music_icon.svg" />

# 🎵 Spotify to YTMusic

### Herramienta CLI para transferir playlists de Spotify a YouTube Music 🚀

<p align="center">
  <b>Spotify to YTMusic</b> es una utilidad de línea de comandos desarrollada en Python que permite migrar playlists, canciones favoritas y bibliotecas musicales desde Spotify hacia YouTube Music de forma rápida y automatizada.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-CLI%20Tool-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Spotify-Migration-1DB954?style=for-the-badge&logo=spotify">
  <img src="https://img.shields.io/badge/YouTube%20Music-Transfer-red?style=for-the-badge&logo=youtube">
  <img src="https://img.shields.io/badge/Open%20Source-Automation-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-preview">Preview</a> •
  <a href="#-características">Características</a> •
  <a href="#-comandos-disponibles">Comandos</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a>
</p>

</div>

---

# 🌌 Acerca de Spotify to YTMusic

**Spotify to YTMusic** es una herramienta diseñada para facilitar la migración de contenido musical entre Spotify y YouTube Music utilizando automatización mediante APIs oficiales.

La herramienta permite:

- 🎵 Transferir playlists
- ❤️ Migrar canciones favoritas
- ☁️ Sincronizar bibliotecas musicales
- 🔄 Actualizar playlists automáticamente
- 📚 Transferir todas las playlists de un usuario
- 🗑️ Eliminar playlists en YouTube Music

El proyecto está orientado al aprendizaje y práctica de:

- Python Automation
- CLI Development
- APIs REST
- OAuth Authentication
- Music Automation
- Data Migration
- YouTube Music API

---

# 📸 Preview

<div align="center">

<img src="https://raw.githubusercontent.com/sigma67/spotify_to_ytmusic/master/docs/demo.png" width="900"/>

</div>

---

# ✨ Características

# 🎵 Transferencia Musical

- 🔄 Transferir playlists Spotify → YouTube Music
- ❤️ Migrar canciones favoritas
- 📚 Transferir playlists completas
- ☁️ Sincronización automática
- ⚡ Procesamiento rápido

---

## 👤 Gestión de Usuarios

- 🎧 Migración de playlists públicas
- 🔐 Soporte OAuth Spotify
- ❤️ Importación de Liked Songs
- 🌎 Gestión de múltiples playlists

---

## 🔥 Automatización

- ⚡ Actualización automática de playlists
- 🔄 Sincronización incremental
- 🗑️ Eliminación automática
- 📊 Logs detallados
- 📄 Exportación de canciones no encontradas

---

## 📱 Herramienta CLI

- 💻 Línea de comandos moderna
- ⚡ Fácil de usar
- 🎵 Integración APIs musicales
- 📦 Instalación rápida
- 🔧 Configuración flexible

---

# 🌐 Integración Spotify & YouTube Music

## 🎧 Plataformas compatibles

- 💚 Spotify
- ▶️ YouTube Music

---

## 🔐 Autenticación

La herramienta soporta:

- Spotify OAuth
- YouTube OAuth
- Private playlists
- Liked songs access
- API credentials

---

# 🛠️ Tecnologías Utilizadas

## 🐍 Backend & CLI

<p>
  <img src="https://skillicons.dev/icons?i=python" />
</p>

- Python 3.10+
- CLI scripting
- OAuth Authentication
- REST APIs

---

## ⚙️ Librerías y Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github" />
</p>

### Dependencias principales

- ytmusicapi
- requests
- Spotify Web API
- argparse
- OAuth libraries

---

# 📂 Estructura del Proyecto

```bash
spotify_to_ytmusic/
│
├── spotify_to_ytmusic/      # Código principal
├── docs/                    # Documentación
├── tests/                   # Pruebas
├── settings.ini             # Configuración
├── requirements.txt
├── pyproject.toml
└── README.md
```

---

# ⚡ Instalación

## 1️⃣ Instalar Python

Requiere:

```bash
Python 3.10+
```

---

## 2️⃣ Instalar pipx

```bash
pip install pipx
```

---

## 3️⃣ Configurar entorno

```bash
pipx ensurepath
```

---

## 4️⃣ Instalar herramienta

```bash
pipx install spotify_to_ytmusic
```

---

# 🔐 Configuración

## 1️⃣ Crear App Spotify

Ir a:

```bash
https://developer.spotify.com/dashboard
```

---

## 2️⃣ Configurar YouTube Music API

Seguir instrucciones de:

```bash
https://ytmusicapi.readthedocs.io/en/stable/setup/oauth.html
```

---

## 3️⃣ Ejecutar setup

```bash
spotify_to_ytmusic setup
```

---

## 4️⃣ Configurar Redirect URI

Usar:

```txt
https://127.0.0.1
```

---

# 🚀 Uso Básico

## 🎵 Transferir playlist

```bash
spotify_to_ytmusic create <spotifylink>
```

Ejemplo:

```bash
spotify_to_ytmusic create https://open.spotify.com/playlist/xxxxx
```

---

## ❤️ Transferir canciones favoritas

```bash
spotify_to_ytmusic liked
```

---

## 📚 Transferir todas las playlists

```bash
spotify_to_ytmusic all <spotifyuserid>
```

---

## 🔄 Actualizar playlist existente

```bash
spotify_to_ytmusic update
```

---

## 🗑️ Eliminar playlists

```bash
spotify_to_ytmusic remove
```

---

# 🎛️ Comandos Disponibles

## 📦 Subcomandos CLI

```bash
setup       # Configurar credenciales
create      # Crear playlist
update      # Actualizar playlist
remove      # Eliminar playlists
all         # Transferir todas las playlists
liked       # Transferir liked songs
```

---

# 🔥 Funcionalidades Técnicas

## 🌐 APIs Integradas

- Spotify Web API
- YouTube Music API
- OAuth Authentication
- Playlist synchronization

---

## ⚡ Sistema CLI

- Argument parsing
- Config files
- Command automation
- Progress logging

---

## 📊 Gestión de Datos

- Playlist migration
- Song matching
- Duplicate handling
- Error reporting

---

# 🧠 Objetivos del Proyecto

## 🎯 Aprender y practicar

- Python CLI
- APIs REST
- OAuth Authentication
- Automatización musical
- Data migration
- Python scripting
- Music platform integration
- Herramientas Open Source

---

# 📊 Roadmap

## 🚧 Próximamente

- 🎵 Sync bidireccional
- ☁️ Cloud backup
- ❤️ Auto-liked sync
- 📱 Interfaz gráfica GUI
- 🔥 Smart matching IA
- ⚡ Multi-thread processing
- 📊 Dashboard estadísticas
- 🚀 Optimización avanzada

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Haz Fork del proyecto
2. Crea una rama

```bash
git checkout -b feature/nueva-funcion
```

3. Realiza cambios
4. Haz commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

5. Haz push

```bash
git push origin feature/nueva-funcion
```

6. Abre un Pull Request 🚀

---

# 👨‍💻 Autor

<div align="center">

## sigma67

Developer enfocado en automatización, herramientas CLI y migración de plataformas musicales.

</div>

---

# 🌟 Apoya el Proyecto

Si te gusta Spotify to YTMusic:

⭐ Dale una estrella al repositorio  
🍴 Haz Fork del proyecto  
📢 Compártelo con otros desarrolladores

---

# 📜 Licencia

Proyecto Open Source desarrollado para automatización y migración de contenido musical.

---

<div align="center">

### 🎵 Spotify to YTMusic — Migra tu música entre plataformas fácilmente.

</div>
