# Caja de Herramientas Matemáticas {#caja-herramientas}

Este capítulo contiene la **Caja de Herramientas de Matemáticas UCES**, una aplicación interactiva desarrollada en `R`, `Shiny` y `Flexdashboard` que permite explorar de forma dinámica diversos conceptos de:

- Aritmética y preliminares
- Álgebra básica y lineal
- Trigonometría
- Cálculo diferencial, integral y de varias variables
- Ecuaciones diferenciales ordinarias (EDO)
- Análisis numérico

La aplicación fue creada por el equipo de trabajo conformado por el profesor Carlos Andrés Escobar Guerra, Pablo Andrés Guzmán, John Jairo Estrada Álvarez y Juan Alberto Arias Quiceno.

---

## Aplicación interactiva

Una vez desplegada la aplicación en shinyapps.io, podés abrirla desde el siguiente botón.

> **Nota:** shinyapps.io no permite incrustar sus aplicaciones dentro de iframes de sitios externos por políticas de seguridad. Por eso la app se abre en una nueva pestaña, lo cual además evita que el navegador se sobrecargue de memoria.

<p style="text-align:center; margin-top:1rem;">
  <a href="https://clasesuces551.shinyapps.io/CajaHerramientasMateUno1/#section-preliminares" 
     target="_blank" 
     class="btn btn-primary" 
     style="padding: 10px 20px; font-size: 1.1em; background-color: #2563eb; color: white; text-decoration: none; border-radius: 6px;">
    ▶️ Abrir Caja de Herramientas (nueva pestaña)
  </a>
</p>

---

## Ejecución local

Si preferís correr la aplicación en tu propia computadora, asegurate de tener todos los archivos en la misma carpeta y ejecutá:

```r
rmarkdown::run("CajaHerramientasMateUno1.Rmd")
```

### Requisitos

```r
install.packages(c(
  "flexdashboard", "shiny", "plotly", "ggplot2", "dplyr",
  "Deriv", "deSolve", "scatterplot3d", "plot3D", "knitr",
  "kableExtra", "lubridate", "magrittr", "htmlTable",
  "latex2exp", "png", "readbitmap", "shape",
  "fractional", "FRACTION"
))
```

### Estructura de archivos necesaria

```
Nueva_Caha_Herramientas/
├── CajaHerramientasMateUno1.Rmd
├── R/
│   └── helpers.R
├── modules/
│   ├── preliminares.Rmd
│   ├── algebra_basica.Rmd
│   ├── algebra_lineal.Rmd
│   ├── trigonometria.Rmd
│   ├── calculo_diferencial.Rmd
│   ├── calculo_integral.Rmd
│   ├── calculo_varias_var.Rmd
│   ├── edo.Rmd
│   └── analisis_numerico.Rmd
└── *.png (imágenes de soporte)
```

---

## Despliegue en shinyapps.io

Para que la app esté disponible 24/7 y se pueda incrustar en este libro sin necesidad de correr nada en R localmente, seguí estos pasos:

1. **Crear cuenta** en [shinyapps.io](https://www.shinyapps.io/) (el plan gratuito es suficiente para uso académico).
2. **Configurar el token**: en el panel de shinyapps.io, ir a **Tokens** → copiar el comando `rsconnect::setAccountInfo(...)` y ejecutarlo una sola vez en R.
3. **Ejecutar el despliegue**: desde la carpeta de la aplicación corré:
   ```r
   source("deploy.R")
   ```
   Eso ejecuta internamente:
   ```r
   rsconnect::deployDoc("CajaHerramientasMateUno1.Rmd",
                        appName = "caja-herramientas-mate-uces")
   ```
4. **Copiar la URL** resultante (aparecerá en la consola al finalizar) y pegarla en el `src` del iframe del archivo `Cap17_CajaHerramientas.Rmd`.
5. **Volver a renderizar el bookdown** (`source("render.R")`) para que el iframe quede activo.

> **Nota sobre el plan gratuito:** incluye 25 horas de uso activo al mes. Si la app no se usa, el servidor se duerme y se reactiva automáticamente cuando alguien entra (puede tardar unos segundos el primer acceso).
