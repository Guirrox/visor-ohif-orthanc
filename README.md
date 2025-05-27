# 🖥️ Visor Médico OHIF + Orthanc (Docker)

Este proyecto proporciona una solución sencilla para desplegar un visor médico DICOM usando **OHIF** como frontend y **Orthanc** como servidor PACS, todo con Docker.

---

## 🚀 Instalación rápida

### ✅ Requisitos previos

- [Docker](https://docs.docker.com/get-docker/)
- [Git](https://git-scm.com/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### 📦 Pasos para desplegar

```bash
docker network create pacs

# 1. Clona este repositorio
git clone https://github.com/Guirrox/ohif-orthanc.git
cd ohif-orthanc

# 2. Levanta los servicios
sudo docker compose up -d
