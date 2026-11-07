# Bruno Fitness Tracker para Android

Esta carpeta contiene la versión instalable como PWA (Progressive Web App).

## Publicación gratuita con GitHub Pages

1. Entra a GitHub y crea un repositorio nuevo, por ejemplo `bruno-fitness-tracker`.
2. Descomprime este ZIP en tu computadora.
3. Sube **todo el contenido** de esta carpeta a la raíz del repositorio: `index.html`, `manifest.webmanifest`, `sw.js` y la carpeta `icons`.
4. En el repositorio abre **Settings → Pages**.
5. En **Build and deployment**, elige **Deploy from a branch**, selecciona `main` y `/ (root)`, y guarda.
6. Espera a que GitHub Pages publique el sitio. La dirección tendrá esta forma:
   `https://TU-USUARIO.github.io/bruno-fitness-tracker/`

## Instalar en Android

1. Abre esa dirección en **Google Chrome** en tu Android.
2. Espera unos segundos a que cargue por completo.
3. Pulsa **Instalar app** si aparece el botón dentro de la aplicación; también puedes abrir el menú ⋮ de Chrome y elegir **Instalar aplicación** o **Añadir a pantalla principal**.
4. Confirma la instalación. Verás el icono Bruno Fitness en tu pantalla de inicio.

## Datos y privacidad

- Los registros se guardan localmente en el navegador/dispositivo (localStorage); no se suben automáticamente a una cuenta ni se sincronizan entre dispositivos.
- Usa las opciones de copia de seguridad/exportación de la aplicación periódicamente.
- No borres los datos del sitio ni el almacenamiento de Chrome si quieres conservar tus registros.
- El modo sin conexión estará disponible después de abrir la aplicación una primera vez con internet.

## Actualizar la aplicación

Cuando subas una nueva versión, reemplaza los archivos del repositorio y vuelve a abrir la app. El service worker actualiza la caché.
