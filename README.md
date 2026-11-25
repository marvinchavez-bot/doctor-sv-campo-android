# Doctor SV Campo para Android

Descarga la aplicación desde [Releases](https://github.com/marvinchavez-bot/doctor-sv-campo-android/releases).

## Versión actual

- Versión visible: **1.0.0.1**.
- Código interno de Android: **29**.
- [Descargar APK](https://github.com/marvinchavez-bot/doctor-sv-campo-android/releases/download/v1.0.0.1/Doctor-SV-Campo-1.0.0.1.apk).

## Publicar próximas actualizaciones

1. Compilar la APK con la misma firma y un código interno mayor: 30, 31, etc. La siguiente versión visible puede ser 1.0.0.2.
2. Crear un nuevo release y adjuntar la APK firmada.
3. Verificar su descarga y calcular su SHA-256.
4. Actualizar `update.json` en la rama `main` con `versionName`, `versionCode`, `url`, `sha256` y `notes`.
5. La app consulta ese manifiesto y valida archivo, paquete, código interno y firma antes de abrir el instalador de Android.

Las instalaciones anteriores reciben el anuncio inicial desde el servidor de la app. No se debe retroceder el código interno aunque cambie la numeración visible.

Este repositorio distribuye instaladores. Las claves de firma, contraseñas, datos del personal y credenciales del servidor se conservan fuera de GitHub.
