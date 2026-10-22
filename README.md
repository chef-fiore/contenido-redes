# Kit de contenido Fiore

Página para descargar todo el contenido de Instagram de @viandas.fiore: feed, carruseles, reels, historias, destacadas, textos y marca.

## Cómo publicarla en GitHub Pages

1. En GitHub, creá un repositorio nuevo, por ejemplo `kit`.
2. **Add file → Upload files**. GitHub deja subir hasta 100 archivos por vez, así que hacelo en dos tandas:
   - Primera tanda: `index.html`, `README.md` y la carpeta `files`.
   - Segunda tanda: la carpeta `thumbs`.
   Arrastrá las carpetas enteras: GitHub respeta la estructura.
3. **Settings → Pages → Build and deployment**: "Deploy from a branch", rama `main`, carpeta `/ (root)`, **Save**.
4. En uno o dos minutos queda en `https://chef-fiore.github.io/kit/` (o el nombre que le hayas puesto al repositorio).

## Qué hay en cada carpeta

- `index.html`: la página.
- `files/`: los archivos en calidad completa, los que se descargan.
- `thumbs/`: versiones livianas para mostrar en la página. No se descargan.
