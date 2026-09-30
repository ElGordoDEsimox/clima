# Cielo para Android

App sencilla del clima, con búsqueda de ciudades y pronóstico actual de Open-Meteo. Requiere conexión a Internet.

## Generar el APK

1. Subí esta carpeta a un repositorio de GitHub.
2. En **Actions**, ejecutá **Build APK** (o esperá a que termine la compilación automática al subir cambios).
3. Abrí la ejecución completada y descargá el artefacto **cielo-debug-apk**. Dentro está `app-debug.apk`, listo para instalar en un teléfono Android.

También podés compilar localmente con Java 17 y Gradle: `gradle assembleDebug`. El APK se guarda en `app/build/outputs/apk/debug/app-debug.apk`.

La compilación de GitHub Actions crea un APK de depuración para instalar y probar; no es un paquete firmado para publicar en Google Play. El pronóstico usa Open-Meteo y la ciudad por defecto es Buenos Aires.
