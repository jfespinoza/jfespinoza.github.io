# Sitio académico de Jesús Francisco Espinoza Fierro

Este repositorio publica el sitio académico disponible en <https://jfespinoza.github.io>.

## Estructura

- `index.html`: portada e índice general de proyectos académicos.
- `curso-algebra-2026-2/`: versión publicada del libro del curso de Álgebra 2026-2.
- `diplomado-interncional-modelado-simulaciones-2025/`: materiales publicados del Diplomado Internacional: Modelado Matemático y Simulaciones.
- `proyectos/curso-algebra-2026-2/`: archivos fuente en Quarto del curso de Álgebra.
- `.github/workflows/`: automatización que renderiza y publica el curso de Álgebra.

Los materiales del Diplomado que permanecen en el nivel superior se conservan únicamente como copias de compatibilidad para no interrumpir enlaces directos compartidos con anterioridad. Las referencias actuales deben utilizar el directorio público del Diplomado.

## Criterios para proyectos futuros

Cada nuevo proyecto debe publicarse en un directorio propio con un identificador breve y estable. Sus páginas y recursos deben usar rutas relativas y permanecer autocontenidos dentro de ese directorio. La portada se actualiza únicamente para incorporar el título, la categoría, una descripción breve y el enlace público del nuevo proyecto.

Los archivos fuente que requieran compilación deben conservarse en `proyectos/<identificador>/`; el resultado publicado debe ubicarse en `/<identificador>/`. Los sitios estáticos que no requieran compilación pueden mantenerse directamente en su directorio público.
