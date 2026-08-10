# Álgebra 22017 · Semestre 2026-2

Libro Quarto del curso de Álgebra impartido por el Dr. Jesús Francisco Espinoza Fierro en la Universidad de Sonora. El mismo material atiende a los grupos 21 de Ingeniería en Materiales y 29 de Ingeniería en Tecnología Electrónica.

Sitio público: <https://jfespinoza.github.io/curso-algebra-2026-2/>

## Contenido

- Información oficial del espacio educativo.
- Metodología de trabajo.
- Evaluación, asistencia y calendario.
- Seis unidades del programa.
- Sesiones diarias con la secuencia Explicación–Ejemplos–Actividad.
- Notación y bibliografía.

## Actualización de una sesión

1. Copiar `plantillas/plantilla-sesion.qmd` a `sesiones/AAAA-MM-DD-sesion-NN.qmd`.
2. Sustituir el título, la fecha y el contenido de la plantilla.
3. Agregar el archivo a la unidad correspondiente en `_quarto.yml`.
4. Ejecutar `quarto render` y revisar `_site/index.html`.
5. Confirmar los cambios en GitHub. La publicación se actualiza automáticamente.

## Renderizado local

Se requiere [Quarto](https://quarto.org/).

```bash
quarto preview
```

Para generar el sitio sin iniciar un servidor:

```bash
quarto render
```

## Criterios editoriales

- Definir la notación antes de utilizarla.
- Conservar una redacción propia; no transcribir el libro de texto.
- Incluir al menos un ejemplo razonado y una actividad por sesión.
- Verificar resultados, ecuaciones, enlaces internos y visualización móvil antes de publicar.
- No incorporar nombres, calificaciones ni datos personales de estudiantes.

