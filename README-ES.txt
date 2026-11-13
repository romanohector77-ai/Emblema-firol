EMBLEMA FIROL - KIT ANDROID (prototipo inicial)

Este paquete NO es todavía una APK. Contiene el proyecto Android y un flujo de GitHub Actions
para compilar una APK de prueba en la nube, sin instalar Android Studio en el teléfono.

PASOS DESDE ANDROID:
1. Crear una cuenta gratuita en github.com e iniciar sesión.
2. Crear un repositorio nuevo llamado emblema-firol (público o privado).
3. Subir el contenido de este ZIP al repositorio, conservando las carpetas y archivos.
4. Abrir la pestaña Actions del repositorio y habilitar GitHub Actions si lo solicita.
5. Ejecutar "Build Emblema Firol APK" con el botón Run workflow (o esperar al primer push).
6. Cuando termine en verde, abrir esa ejecución, bajar el artefacto "Emblema-Firol-APK".
7. Extraer el artefacto ZIP y abrir app-debug.apk para instalarlo. Android puede pedir permiso
   para instalar desde el navegador/archivos.

Requisitos: Android 6.0 o posterior para la app. La APK debug es de prueba y no está publicada
en Play Store. Este primer prototipo usa WebView offline y gráficos 2D isométricos sencillos;
no representa todavía modelos 3D comerciales. Próximas versiones añadirán arte y animaciones.
