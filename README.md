# Sitio Web de Hoja de Vida (GitHub Pages)

Este repositorio contiene un sitio estático donde la **página de inicio** muestra tu hoja de vida completa como PDF (todas las páginas, con desplazamiento).

## Estructura
```
/
├─ index.html
├─ css/
│  └─ styles.css
└─ assets/
   └─ hoja-de-vida.pdf
```

## Cómo publicarlo en GitHub Pages

### Opción A · Sitio de Usuario (recomendado si aún no tienes uno)
1. Crea un repositorio llamado **`TU-USUARIO.github.io`** (reemplaza por tu usuario real de GitHub).
2. Sube los archivos de esta carpeta (mantén las rutas).
3. Ve a **Settings → Pages** y verifica que se publique desde la rama `main` (carpeta `/root`).
4. Espera a que se construya. Tu web quedará en `https://TU-USUARIO.github.io/`.

### Opción B · Sitio de Proyecto
1. Crea un repositorio cualquiera, por ejemplo **`cv-jesus-romero`**.
2. Sube los archivos de esta carpeta.
3. Ve a **Settings → Pages**:
   - **Source**: `main`
   - **Branch folder**: `/ (root)`
4. La URL será algo como `https://TU-USUARIO.github.io/cv-jesus-romero/`.

> Si usas la Opción B, ajusta los enlaces relativos si mueves archivos a subcarpetas.

## Consejos
- Si tu PDF cambia, simplemente reemplaza `assets/hoja-de-vida.pdf` por la versión nueva (mismo nombre).
- Algunos navegadores corporativos bloquean visores PDF embebidos. Usa el botón **Descargar PDF**.
- Revisa que no publiques datos sensibles que no quieras hacer públicos.
