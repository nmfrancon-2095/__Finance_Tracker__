# 💰 Mi Dinero · Tracker Financiero Personal

PWA (Progressive Web App) — instalable en iPhone, Android, Mac y Windows.

## Cómo publicar en GitHub Pages (gratis)

### Paso 1 — Crear repositorio
1. Ve a [github.com](https://github.com) e inicia sesión
2. Clic en **"New repository"** (botón verde arriba a la derecha)
3. Nombre: `mi-dinero` (o el que quieras)
4. Visibility: **Public** ← importante para GitHub Pages gratis
5. Clic en **"Create repository"**

### Paso 2 — Subir los archivos
1. En la página del repositorio recién creado, clic en **"uploading an existing file"**
2. Arrastra TODOS los archivos de esta carpeta:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `.nojekyll`
   - carpeta `icons/` (con icon-192.png e icon-512.png)
3. Clic en **"Commit changes"**

### Paso 3 — Activar GitHub Pages
1. Ve a **Settings** → **Pages** (en el menú izquierdo)
2. Source: **"Deploy from a branch"**
3. Branch: **main** → folder: **/ (root)**
4. Clic en **Save**
5. Espera ~2 minutos

Tu app estará en: `https://TU-USUARIO.github.io/mi-dinero/`

## Cómo instalar en tu dispositivo

### iPhone / iPad
1. Abre la URL en **Safari** (no Chrome)
2. Toca el ícono de compartir (□↑)
3. Selecciona **"Añadir a pantalla de inicio"**
4. ¡Listo! Aparece como app nativa

### Android
1. Abre la URL en **Chrome**
2. Aparecerá un banner "Instalar app" automáticamente, O
3. Menú (⋮) → **"Añadir a pantalla de inicio"**

### Mac / Windows (escritorio)
1. Abre la URL en **Chrome** o **Edge**
2. En la barra de direcciones verás un ícono de instalar (⊕)
3. Clic → **"Instalar"**
4. Aparece en tu dock / barra de tareas como app

## Notas
- Los datos se guardan en el navegador del dispositivo (localStorage)
- Para transferir datos entre dispositivos: Configuración → Exportar JSON → importar en el otro
- Funciona offline una vez instalada
