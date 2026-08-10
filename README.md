# Presencia.Lab

Sitio web de Presencia.Lab — diseño y desarrollo de espacios web para emprendimientos.

## Estructura

```
presencia-lab/
├── index.html                    → el sitio (todo el CSS/JS está inline en este archivo)
├── assets/
│   └── images/
│       ├── site/                 → fotos generales del sitio (equipo, proceso, etc.)
│       └── portfolio/            → capturas o fotos de trabajos (RenderAzo, Romina G, etc.)
└── README.md
```

## Cómo agregar una imagen

1. Copiá la imagen dentro de `assets/images/site/` o `assets/images/portfolio/` según corresponda.
2. En `index.html`, agregá una etiqueta como:
   ```html
   <img src="assets/images/portfolio/renderazo-captura.jpg" alt="Descripción de la imagen">
   ```
3. Commiteá y pusheá los cambios — Netlify va a redesplegar el sitio solo.

## Cómo hacer cambios

- Edición rápida (texto, un color, un link): editá `index.html` directo en GitHub (ícono de lápiz en la vista del archivo), escribí un mensaje de commit y confirmá. Netlify lo publica solo en 1-2 minutos.
- Cambios más grandes: cloná el repo localmente, editá con tu editor de código, probá abriendo `index.html` en el navegador, y después `git add . && git commit -m "mensaje" && git push`.

## Deploy

Este repo está pensado para conectarse a Netlify con "Import from Git" → cada push a `main` redespliega el sitio automáticamente. No hace falta build command ni carpeta de publicación especial: el sitio raíz (`/`) ya es el publish directory.
