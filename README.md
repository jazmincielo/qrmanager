# QRManager - Sistema de Gestión y Generación de Códigos QR

QRManager es una aplicación web monolítica construida con **NiceGUI**, **SQLModel**, **SQLite**, **qrcode** y autenticación basada en sesiones.

## 🏗️ Arquitectura del Proyecto
El proyecto utiliza una arquitectura monolítica dividida en capas claras de presentación, lógica de negocio y persistencia de datos.

## 🚀 Requisitos Previos
- Python 3.11+
- Docker (Opcional)
- Git

## 🛠️ Instalación y Ejecución Local
1. **Clonar repositorio:** `git clone https://github.com/jazmincielo/qrmanager.git`
2. **Crear entorno virtual:** `python -m venv .venv`
3. **Activar entorno:** `.venv\Scripts\activate` (Windows) o `source .venv/bin/activate` (Linux/Mac)
4. **Instalar dependencias:** `pip install -r requirements.txt`
5. **Ejecutar aplicación:** `python -m app.main`

## 🐳 Ejecución con Docker
```bash
docker build -t qrmanager-app .
docker run -d -p 8080:8080 --name qrmanager_container qrmanager-app
```

