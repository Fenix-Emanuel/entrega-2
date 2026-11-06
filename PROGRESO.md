# Balance Performance — Proyecto mejora (paso 2)

Rediseño como marca deportiva premium, hecho por Ignis Studio.

- `index.html`: sitio nuevo en una sola página (hero cinematográfico, manifiesto, método en paneles horizontales, programas, tienda, nosotros, contacto).
- Stack: HTML/CSS/JS + GSAP 3.12.5 (ScrollTrigger) + Lenis 1.1.13 desde CDN. Sin build.
- Respeta `prefers-reduced-motion` (versión estática) y en pantallas menores a 900 px los paneles del método van en columna.
- `v1/`: versión original (Bootstrap + SCSS), intacta. Las imágenes se comparten desde `img/`.
- `pages/*.html`: redirigen las URLs viejas a la sección nueva correspondiente.
