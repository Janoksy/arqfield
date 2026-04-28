# ArqField 🏺
### App de Registro Arqueológico de Campo — PWA Offline

---

## ¿Qué es esto?
App móvil para registrar fichas arqueológicas de recolección superficial.
Funciona **con y sin internet**. Se instala en iOS/Android como app nativa.

---

## Cómo publicar en GitHub Pages (paso a paso)

### Paso 1 — Crear cuenta en GitHub
1. Ve a [github.com](https://github.com) y crea una cuenta gratuita si no tienes una.

### Paso 2 — Crear repositorio nuevo
1. Haz clic en el botón verde **"New"** (o el símbolo +).
2. Nombre del repositorio: `arqfield` (en minúsculas, sin espacios).
3. Marca la opción **"Public"** (debe ser público para GitHub Pages gratis).
4. Haz clic en **"Create repository"**.

### Paso 3 — Subir los archivos
En la página de tu repositorio vacío:
1. Haz clic en **"uploading an existing file"**.
2. Arrastra y suelta **todos** los archivos de esta carpeta:
   - `index.html`
   - `sw.js`
   - `manifest.json`
   - La carpeta `.github/` completa (con su contenido)
3. Escribe un mensaje como `"Primera versión ArqField"`.
4. Haz clic en **"Commit changes"**.

### Paso 4 — Activar GitHub Pages
1. Ve a **Settings** (pestaña de configuración del repositorio).
2. En el menú izquierdo, haz clic en **"Pages"**.
3. En "Source", selecciona **"GitHub Actions"**.
4. Guarda los cambios.

### Paso 5 — Esperar el deploy (1-2 minutos)
1. Ve a la pestaña **"Actions"** del repositorio.
2. Verás un workflow corriendo. Cuando aparezca ✅ verde, está listo.
3. Tu URL será: `https://TU_USUARIO.github.io/arqfield/`

---

## Cómo instalar en iPhone (iOS)
1. Abre Safari y ve a la URL de la app.
2. Toca el botón compartir ⬆️ (abajo al centro).
3. Selecciona **"Añadir a pantalla de inicio"**.
4. Toca **"Añadir"**.
5. La app aparece como ícono en tu pantalla. ¡Lista para usar offline!

> **Importante:** Debe abrirse al menos una vez con internet para que se cachee.
> Después funciona sin señal indefinidamente.

---

## Compartir con el equipo
Una vez publicada, comparte la URL con cada integrante del equipo.
Cada persona la instala en su dispositivo siguiendo el Paso de iOS.
Cada dispositivo guarda sus propias fichas localmente.

---

## Archivos del proyecto
```
arqfield/
├── index.html          ← App completa
├── sw.js               ← Service Worker (soporte offline)
├── manifest.json       ← Configuración PWA (instalación iOS/Android)
├── README.md           ← Este archivo
└── .github/
    └── workflows/
        └── deploy.yml  ← Deploy automático a GitHub Pages
```

---

## Próximas versiones planificadas
- [ ] Más tipos de fichas (pozos de sondeo, estructuras, etc.)
- [ ] Vista de mapa con todos los hallazgos
- [ ] Exportación a PDF
- [ ] Sincronización entre dispositivos (Google Drive)
