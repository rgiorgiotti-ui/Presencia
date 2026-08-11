# Presencia.Lab

Sitio web de Presencia.Lab — diseño y desarrollo de espacios web para emprendimientos.

## Estructura

```
presencia-lab/
├── index.html      → el sitio (todo el CSS/JS está inline en este archivo)
├── images/          → TODAS las fotos van acá, sin subcarpetas
└── README.md
```

## Imágenes que el sitio ya está esperando

Subí estos archivos directo a la carpeta `images/` (un solo nivel, nada de subcarpetas). Mientras no estén, se ve un color de respaldo — nada se rompe.

| Archivo | Dónde se usa |
|---|---|
| `portfolio-renderazo.png` | Tarjeta de RenderAzo |
| `portfolio-rominag.png` | Tarjeta de Portfolio profesional |
| `portfolio-coachingsync.png` | Tarjeta de CoachingSync |
| `template-1.png` | Carrusel de templates |
| `template-2.png` | Carrusel de templates |
| `template-3.png` | Carrusel de templates |
| `template-4.png` | Carrusel de templates |

Los nombres tienen que ser exactos (minúsculas, sin espacios, con guion medio donde corresponda).

## Cómo subir una imagen

1. En GitHub → `Add file` → `Upload files`.
2. Arrastrá la imagen.
3. En el campo de nombre que aparece debajo de la miniatura, escribí: `images/nombre-exacto.png`
4. Confirmá el commit — Netlify redespliega solo.

## Cómo hacer cambios al sitio

- Edición rápida (texto, un color, un link): editá `index.html` directo en GitHub (ícono de lápiz), escribí un mensaje de commit y confirmá.
- Cambios más grandes: cloná el repo con GitHub Desktop, editá localmente, y hacé commit + push.
