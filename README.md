# Propuesta web · GetRebelEdits

One page para presentar la propuesta de rediseño web a GetRebelEdits. HTML y CSS estáticos, sin dependencias.

## Archivos

- `index.html`: la página.
- `styles.css`: estilos.
- `propuesta-completa.pdf`: la propuesta completa, descargable desde la página.
- `robots.txt` y la etiqueta `noindex`: piden a los buscadores no mostrar la página.
- `.nojekyll`: publica los archivos tal cual en GitHub Pages.

## Antes de publicar

1. En `index.html`, reemplaza `CORREO@EJEMPLO.COM` por tu correo o por el enlace a tu agenda.
2. Si Sandra tiene portafolio, agrega su enlace en la sección "Quiénes somos".

## Publicar en GitHub Pages

1. En GitHub, crea un repositorio nuevo (por ejemplo, `propuesta-getrebeledits`).
2. Sube todos los archivos de esta carpeta, incluido `.nojekyll`.
3. Ve a **Settings → Pages**.
4. En **Source** elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`, y guarda.
5. En 1 o 2 minutos la página queda en `https://TU-USUARIO.github.io/propuesta-getrebeledits/`.

Desde la terminal:

```bash
git remote add origin https://github.com/TU-USUARIO/propuesta-getrebeledits.git
git push -u origin main
```

## Privacidad

GitHub Pages es público: cualquiera con el enlace puede ver la página, aunque no aparezca en Google. Usa un nombre de repositorio poco obvio y despublica la página (Settings → Pages → Unpublish) cuando el cliente decida.
