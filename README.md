# Mercadona Market (React + Vite + Bun)

## Cómo desplegar en Netlify

1. **Descarga el proyecto:**
   - Descarga la carpeta `torbay-clone` completa como ZIP y descomprímela en tu computadora.

2. **Crea una cuenta en [Netlify](https://netlify.com/)** (es gratis).

3. **Nuevo sitio:**
   - Haz clic en **Add new site → Import an existing project**.
   - Sube tu carpeta (o selecciona desde Git si lo tienes subido).

4. **Selecciona configuración personalizada:**
   - **Build command:** `bun run build` (o `npm run build` si prefieres cambiar scripts a npm)
   - **Publish directory:** `dist`

5. **Espera que termine el deploy** y tendrás una URL pública para probar el sitio completo.


## Notas útiles
- **Routing SPA:** Ya está configurado para navegaciones internas (por ejemplo: /escrow, /mensajes) sin errores 404.
- Si usas npm/yarn, cambia el comando de build a `npm run build` sin problema.
- Si quieres cambiar la URL base de la API, modíficalo en `.env` o usando la variable VITE_API_URL.

## Scripts útiles
- `bun run dev` — inicia el servidor para desarrollo local
- `bun run build` — genera la carpeta `dist`
- `bun run preview` — previsualiza lo generado

¡Listo para la nube!
