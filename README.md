<div align="center">

# NetCrew Client

**Cliente de escritorio oficial para conectarse a redes privadas VPN P2P Mesh gestionadas con [NetCrew](https://netcrew.es).**

[![Última versión](https://img.shields.io/github/v/release/fredeabal/fredeabal-netcrew-app-releases?style=for-the-badge&color=f97316&label=Última%20versión)](https://github.com/fredeabal/fredeabal-netcrew-app-releases/releases/latest)
[![Descargas](https://img.shields.io/github/downloads/fredeabal/fredeabal-netcrew-app-releases/total?style=for-the-badge&color=162136&label=Descargas)](https://github.com/fredeabal/fredeabal-netcrew-app-releases/releases)
![Plataformas](https://img.shields.io/badge/Plataformas-macOS%20%C2%B7%20Windows%20%C2%B7%20Linux-22c55e?style=for-the-badge)
![Motor](https://img.shields.io/badge/Motor-Nebula%20P2P%20Mesh-1e293b?style=for-the-badge)

[Descargar última versión](#-descargas) · [Cómo conectarse](#-cómo-conectarse) · [Primer arranque](#-primer-arranque-por-sistema-operativo) · [Web oficial](https://netcrew.es)

</div>

---

## ✨ Características principales

- **Conexión P2P Mesh cifrada:** comunicación directa y segura entre dispositivos sobre **Nebula**.
- **Importación en segundos:** arrastra tu archivo `.yml` o pega tu enlace temporal (`/connect/...`).
- **Ligero y multiplataforma:** aplicación nativa para **macOS**, **Windows** y **Linux**.
- **Estado en tiempo real:** comprobación automática de conectividad con la red VPN.

---

## 📦 Descargas

> [!TIP]
> Los enlaces de la tabla siempre apuntan a la **última versión estable** publicada.

| Plataforma | Arquitectura | Formato | Descarga directa |
| :--- | :--- | :--- | :--- |
|  **macOS** | Apple Silicon + Intel (Universal) | `.dmg` | [**Descargar `.dmg`**](https://github.com/fredeabal/fredeabal-netcrew-app-releases/releases/latest/download/NetCrew-Client-macOS.dmg) |
| 🪟 **Windows** | 64-bit (`x64`) | Instalador `.exe` | [**Descargar `.exe`**](https://github.com/fredeabal/fredeabal-netcrew-app-releases/releases/latest/download/NetCrew-Client-Windows-Setup.exe) |
| 🪟 **Windows** | 64-bit (`x64`) | Paquete `.msi` | [**Descargar `.msi`**](https://github.com/fredeabal/fredeabal-netcrew-app-releases/releases/latest/download/NetCrew-Client-Windows.msi) |
| 🐧 **Linux** *(Ubuntu / Debian)* | `amd64` | Paquete `.deb` | [**Descargar `.deb`**](https://github.com/fredeabal/fredeabal-netcrew-app-releases/releases/latest/download/NetCrew-Client-Linux-amd64.deb) |
| 🐧 **Linux** *(Universal)* | `amd64` | `.AppImage` | [**Descargar `.AppImage`**](https://github.com/fredeabal/fredeabal-netcrew-app-releases/releases/latest/download/NetCrew-Client-Linux-amd64.AppImage) |
| 🐧 **Linux** *(Fedora / RHEL)* | `x86_64` | Paquete `.rpm` | [**Descargar `.rpm`**](https://github.com/fredeabal/fredeabal-netcrew-app-releases/releases/latest/download/NetCrew-Client-Linux-x86_64.rpm) |

Todas las versiones anteriores y archivos adicionales están disponibles en la sección de [**Releases**](https://github.com/fredeabal/fredeabal-netcrew-app-releases/releases/latest).

---

## 🚀 Cómo conectarse

1. **Abre NetCrew Client** tras completar la instalación.
2. **Importa tu perfil** arrastrando el archivo `.yml` a la ventana, pulsando **`+`**, o desde **Menú → Importar desde enlace** (`/connect/...`).
3. **Activa el interruptor** del perfil para iniciar la conexión *(el sistema solicitará permisos de administrador para crear la interfaz VPN)*.

---

## 🛠 Primer arranque por sistema operativo

<details>
<summary><b> macOS — Aviso de desarrollador no verificado (Gatekeeper)</b></summary>

Si macOS muestra el aviso *"Apple no ha podido verificar que NetCrew Client no contenga software malicioso"* al abrir la app por primera vez:

1. Pulsa **Aceptar**.
2. Abre **Ajustes del Sistema → Privacidad y seguridad** (sección *Seguridad*, abajo del todo).
3. Pulsa **Abrir de todas formas** junto al aviso de **NetCrew Client**.

</details>

<details>
<summary><b>🪟 Windows — Advertencia de SmartScreen</b></summary>

Si **Windows SmartScreen** muestra una advertencia al ejecutar el instalador `.exe` o `.msi`:

1. Pulsa **Más información**.
2. Selecciona **Ejecutar de todas formas**.

</details>

<details>
<summary><b>🐧 Linux — Permisos para AppImage</b></summary>

Si utilizas el paquete `.AppImage`, asegúrate de darle permisos de ejecución antes de abrirlo:

```bash
chmod +x NetCrew-Client-Linux-amd64.AppImage
./NetCrew-Client-Linux-amd64.AppImage
```

</details>

---

<div align="center">

Este repositorio aloja únicamente los instaladores oficiales compilados de **NetCrew Client**.  
Más información y gestión de redes en **[netcrew.es](https://netcrew.es)**.

</div>
