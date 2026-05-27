---
title: "Proyecto Cuestionarios"
author: "SIM01"
date: "2026-05-26"
site: bookdown::bookdown_site
documentclass: book
output:
  bookdown::gitbook:
    split_by: chapter
    includes:
      in_header: quiz_interactive.html
    config:
      toc:
        before: |
          <li><a href="./">Proyecto Cuestionarios</a></li>
        after: |
          <li><a href="https://github.com/rstudio/bookdown" target="blank">Publicado con bookdown</a></li>
      edit: null
      download: null
      search:
        engine: fuse
      sharing:
        facebook: false
        twitter: false
      info: true
---

# Prefacio {.unnumbered}

Este libro recopila todos los cuestionarios de evaluación desarrollados para el curso SIM01. Cada capítulo corresponde a una evaluación temática diferente, organizada de manera progresiva para facilitar el estudio y la consulta.

## Contenido {.unnumbered}

Los capítulos incluyen evaluaciones sobre:

- Potenciación
- Álgebra (expresiones racionales, despeje de variables, resolución de ecuaciones)
- Desigualdades (con y sin valor absoluto)
- Sistemas de ecuaciones
- Funciones exponenciales y logarítmicas
- Trigonometría
- Planteamiento y solución de problemas

> **Nota:** Estos cuestionarios fueron originalmente desarrollados como tutoriales interactivos en `learnr`. Se han adaptado para funcionar como cuestionarios interactivos en HTML estático: puedes seleccionar respuestas, enviarlas y recibir retroalimentación inmediata sin necesidad de servidor.
