# Registro de Macros

App de registro diario de comidas y macronutrientes, instalable como app en el movil (PWA).

Objetivos configurados: 2000 kcal / 200 g carbohidratos / 58 g grasas / 140 g proteina.

## Archivos

Todos deben estar sueltos en la raiz del repositorio (no dentro de una subcarpeta), con estos nombres exactos:

- `index.html` — la app
- `manifest.json` — configuracion de instalacion
- `service-worker.js` — cache para que funcione sin conexion
- `icon-192.png` / `icon-512.png` — iconos de la app

## Publicar o actualizar en GitHub Pages

1. Entra en el repositorio en github.com.
2. **Add file → Upload files**, arrastra los archivos (al actualizar, simplemente vuelve a subir el/los archivo/s que hayan cambiado; sustituyen a los anteriores).
3. **Commit changes**.
4. La primera vez, activa Pages en **Settings → Pages → Source: Deploy from a branch → Branch: main, carpeta / (root) → Save**.
5. Espera 1-2 minutos. La URL aparece arriba, tipo `https://tu-usuario.github.io/registro-macros/`.

## Instalar en el movil

1. Abre la URL de Pages en Chrome (Android) o Safari (iPhone).
2. Menu (⋮ o icono de compartir) → **"Anadir a pantalla de inicio"** / **"Instalar app"**.

## Datos y backup

Los datos (comidas registradas por dia y alimentos anadidos) se guardan en el propio navegador/dispositivo donde se usa la app, no en GitHub. Usa los botones **Exportar backup / Importar backup** dentro de la app para mover los datos a otro dispositivo o guardarlos a salvo.
