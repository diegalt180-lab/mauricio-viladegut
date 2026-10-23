# Mauricio Viladegut — Portafolio

Portafolio interactivo (sitio estático). No requiere build: `index.html` en la raíz, datos en `data.js` e imágenes en `img/`.

## Subir a GitHub y desplegar en Vercel

1. Crea un repositorio vacío en https://github.com/new (ej. `mauricio-viladegut`), **sin** README ni .gitignore.
2. En esta carpeta, conecta el remoto y empuja (reemplaza `TU-USUARIO`):

   ```bash
   git remote add origin https://github.com/TU-USUARIO/mauricio-viladegut.git
   git push -u origin main
   ```

3. Entra a https://vercel.com/new, importa ese repositorio.
   - **Framework Preset:** Other
   - **Build Command / Output Directory:** déjalos vacíos (sitio estático)
   - Deploy.

Cada `git push` vuelve a desplegar automáticamente.
