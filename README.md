

# Incendio Radar Android

![Incendio Radar Logo](https://github.com/juulsdev/IncendioRadarApp/blob/main/app/src/main/res/mipmap-xxxhdpi/ic_launcher.png)

Flutter · Android · OpenStreetMap · NASA FIRMS API

Incendio Radar Android es la versión nativa para Android de la app de visualización de incendios activos y sus huellas en España y Europa, usando datos en tiempo real de la NASA.

## 📱 Descripción

La app permite:
- Visualizar focos de incendios en un mapa interactivo.
- Consultar detalles de cada incendio (fecha, brillo, FRP, etc).
- Interfaz adaptativa para móvil.

## 🏗️ Estructura del Proyecto

```
IncendioRadarAndroid/
├── android/               # Código nativo y configuración Android
│   ├── app/               # Módulo principal de la app
│   ├── build.gradle.kts   # Configuración Gradle
│   └── ...
└── README.md              # Documentación del proyecto
```

## ⚙️ Subir el código Android a GitHub

1. Crea una carpeta nueva y copia solo la carpeta `android` de tu proyecto Flutter.
2. Inicializa el repositorio:
   ```powershell
   git init
   git add .
   git commit -m "Subir solo la carpeta android"
   git remote add origin https://github.com/tuusuario/IncendioRadarAndroid.git
   git push -u origin master
   ```
   (Reemplaza `tuusuario` y el nombre del repo por los tuyos.)

## 📦 Cómo generar y subir la APK

1. En tu proyecto Flutter original, genera la APK:
   ```powershell
   flutter build apk --release
   ```
   El archivo generado estará en:
   `build/app/outputs/flutter-apk/app-release.apk`

2. Sube la APK a GitHub:
   - Ve a tu repositorio en GitHub.
   - Haz clic en "Releases" > "Draft a new release".
   - Ponle un nombre (ejemplo: `v1.0.0`), una descripción y adjunta el archivo `app-release.apk`.
   - Publica la release.

## ⚠️ Nota

Subir solo la carpeta `android` NO incluye el código fuente de la app Flutter (`lib/`).
No se puede compilar ni ejecutar la app completa solo con la carpeta `android`.

---
IncendioRadapApp – Julia Herrera
