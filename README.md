# Katrielle Control

Aplicación web móvil para gestionar Katrielle Creations.

## Funciones
- Dashboard
- Pedidos
- Clientes
- Agenda
- Finanzas
- LLQP
- Respaldo e importación de datos
- Instalación como app

## Publicar con GitHub Pages
1. Sube `index.html`, `manifest.webmanifest` y `sw.js` a la rama `main`.
2. Abre **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**.
4. Elige `main` y `/root`.
5. Guarda.

La dirección será:
`https://katriellecreations.github.io/katrielle-control/`

## Almacenamiento
Esta primera versión usa almacenamiento local del navegador y permite descargar/importar respaldos JSON. Para sincronización real entre dispositivos debe conectarse a Firebase o Supabase.
