# 📧 Gmail to Google Drive - n8n Automation

![n8n version](https://img.shields.io/badge/n8n-1.0%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-production%20ready-brightgreen)

> Automatización que extrae archivos adjuntos de correos electrónicos en Gmail y los guarda automáticamente en Google Drive
> 
![Workflow n8n](https://github.com/moleculax/gestionaArchivosMailAbjuntos/blob/main/screen.png)
> 
## 📋 Tabla de Contenidos

- [Descripción General](#-descripción-general)
- [Características](#-características)
- [Requisitos Previos](#-requisitos-previos)
- [Instalación y Configuración](#-instalación-y-configuración)
- [Uso](#-uso)
- [Estructura del Workflow](#-estructura-del-workflow)
- [Variables de Entorno](#-variables-de-entorno)
- [Solución de Problemas](#-solución-de-problemas)
- [Personalización](#-personalización)
- [Licencia](#-licencia)

## 🎯 Descripción General

Este workflow de n8n automatiza el proceso de descarga de archivos adjuntos desde correos electrónicos de Gmail y su posterior almacenamiento en carpetas específicas de Google Drive. Ideal para:

- 📎 Automatizar respaldos de facturas y documentos
- 🖼️ Guardar automáticamente imágenes recibidas por email
- 📑 Organizar archivos adjuntos por remitente o asunto
- 🔄 Integrar sistemas legacy que solo envían emails

## ✨ Características

- ✅ Monitoreo automático de bandeja de entrada
- ✅ Soporte para múltiples tipos de archivo (PDF, imágenes, documentos)
- ✅ Organización por carpetas en Google Drive
- ✅ Notificaciones opcionales de éxito/error
- ✅ Logs detallados de cada ejecución
- ✅ Filtrado por remitente, asunto o etiquetas

## 📋 Requisitos Previos

| Recurso | Requisito |
|---------|-----------|
| **n8n** | Versión 1.0+ (self-hosted o cloud) |
| **Gmail** | Cuenta con API habilitada |
| **Google Drive** | Cuenta con espacio disponible |
| **Credenciales OAuth** | Configuradas en Google Cloud Console |

## 🚀 Instalación y Configuración

### 1. Importar el Workflow

```bash
# Clona este repositorio

# O importa manualmente desde la interfaz de n8n:
n8n workflow:import workflow.json
