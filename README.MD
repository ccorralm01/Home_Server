# 🏠 Home Server – Infraestructura autoalojada con Docker Compose

Este repositorio contiene la configuración de mi **Home Server personal**, donde despliego y gestiono distintos servicios autoalojados utilizando **Docker y Docker Compose**.

El objetivo del proyecto es aplicar conocimientos reales de **sistemas, redes, DevOps y backend**, manteniendo una infraestructura funcional, segura y fácilmente escalable.

Para mantener la seguridad de mi configuración todos los datos de caracter sensible expuestos en este repositorio son ejemplos no usados en el despliegue real

---

## 🧱 Tecnologías utilizadas

- Linux (Ubuntu Server)
- Docker
- Docker Compose
- Nginx Proxy Manager
- Servicios self-hosted
- Redes y volúmenes Docker
- HTTPS con certificados Let's Encrypt

---

## 📂 Estructura del repositorio

Cada carpeta representa un servicio independiente desplegado mediante su propio `docker-compose.yml`.

Home_Server/
  jellyfin/
  n8n/
  nginx_proxy_manager/
  owncloud/
  pufferpanel/
  qbittorrent/
  stirling-pdf/
  vaultwarden/
  README.md

---

## 🚀 Servicios desplegados

### 🎬 Jellyfin

Servidor multimedia autoalojado para organizar y reproducir películas, series y música.

- Alternativa open-source a Plex
- Acceso desde múltiples dispositivos
- Transcodificación de vídeo

---

### 🔄 n8n

Herramienta de automatización de flujos de trabajo.

- Conexión entre APIs y servicios
- Automatización de tareas repetitivas

---

### 🌐 Nginx Proxy Manager

Proxy inverso con interfaz gráfica.

- Gestión de dominios y subdominios
- Certificados HTTPS automáticos (Let's Encrypt)
- Centraliza el acceso seguro a todos los servicios

---

### ☁️ OwnCloud

Plataforma de almacenamiento en la nube personal.

- Sincronización de archivos
- Compartición segura
- Alternativa a Google Drive o Dropbox

---

### 🎮 PufferPanel

Panel de control para servidores de juegos.

- Gestión de servidores (por ejemplo, Minecraft)
- Interfaz web intuitiva
- Uso personal y para servidores con amigos

---

### ⬇️ qBittorrent

Cliente BitTorrent con interfaz web.

- Descarga de torrents sin entorno gráfico
- Control remoto desde navegador
- Ideal para servidores siempre encendidos

---

### 📄 Stirling-PDF

Servicio para generar y manipular documentos PDF.

- Conversión desde HTML y otros formatos
- Útil como backend para aplicaciones
- Automatización de generación de PDFs

---

### 🔐 Vaultwarden

Gestor de contraseñas autoalojado basado en Bitwarden.

- Almacenamiento seguro de credenciales
- Compatible con apps y extensiones oficiales
- Ligero y eficiente

---


## 🧠 Objetivo del proyecto

- Aprendizaje práctico de Docker y Docker Compose
- Administración de servicios autoalojados
- Gestión de infraestructura y redes
- Aplicación real de conceptos DevOps
- Entorno controlado para pruebas y automatización

---

## 📌 Notas

- Cada servicio utiliza volúmenes Docker para persistencia de datos
- El acceso externo se gestiona mediante Nginx Proxy Manager
- Proyecto en constante evolución

---

👨‍💻 Autor: César Enrique Corral Menéndez
🔗 GitHub: https://github.com/ccorralm01
