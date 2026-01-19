# 🌸 Geri - Gestor de Álbumes y Fotos

<div align="center">
  <img src="iconpurple.png" alt="Geri Logo" width="120"/>
  
  [![Flutter](https://img.shields.io/badge/Flutter-3.3.0+-02569B?logo=flutter)](https://flutter.dev)
  [![Firebase](https://img.shields.io/badge/Firebase-Enabled-orange?logo=firebase)](https://firebase.google.com)
  [![License](https://img.shields.io/badge/License-Private-red)]()

</div>

---

## Descripción

**Geri** es una aplicación móvil desarrollada en Flutter que permite a los usuarios crear álbumes de fotos privados o compartidos, agregar comentarios a las fotos, recibir notificaciones push y gestionar fotos de forma visual mediante un calendario interactivo.

### Características principales

- 📸 **Gestión de álbumes**: Crea álbumes privados o compartidos
- 💬 **Comentarios en fotos**: Interactúa con tus recuerdos
- 🔔 **Notificaciones push**: Recibe alertas de nuevos comentarios (OneSignal)
- 📅 **Calendario de recuerdos**: Visualiza tus fotos por fecha
- 🔄 **Actualizaciones automáticas**: Sistema in-app para mantener la app siempre actualizada
- ☁️ **Almacenamiento en la nube**: Cloudinary para fotos, Firestore para datos

---

## Tecnologías utilizadas

| Tecnología | Propósito |
|------------|-----------|
| **Flutter 3.3+** | Framework principal |
| **Firebase Auth** | Autenticación de usuarios |
| **Cloud Firestore** | Base de datos en tiempo real |
| **Cloudinary** | Almacenamiento de imágenes |
| **OneSignal** | Notificaciones push |
| **Provider** | Gestión de estado |
| **Cached Network Image** | Caché de imágenes |
---
## Sistema de actualizaciones

- La app incluye un sistema de actualizaciones automáticas in-app
- Al abrir la app, verifica la versión disponible en Firestore
- Si hay una nueva versión, muestra un diálogo
- El usuario puede actualizar con un solo tap
- La descarga e instalación es automática

## Licencia

Este proyecto es privado y de uso personal. 
