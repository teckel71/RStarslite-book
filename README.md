# R-Stars Lite

Versión reducida de [R-Stars: La Guía](https://teckel71.github.io/RStars-book/) para la asignatura **Métodos Aplicados al Análisis del Entorno Empresarial** (Máster Universitario en Iniciativa Empresarial: Análisis y Estrategias, UCLM).

Las prácticas se resuelven con el paquete [`{MATlite}`](https://github.com/teckel71/MATlite):

```r
remotes::install_github("teckel71/MATlite")
```

## Compilar el libro

```r
source("render.R")   # o, desde la terminal: Rscript render.R
```

El libro se genera en `docs/` (publicado con GitHub Pages). `numerar_tablas_figuras.R` es el preprocesador de *R-Stars: La Guía*, ampliado para las funciones de MATlite: las piezas de un resultado (`objeto$pieza`) se muestran una por chunk con la opción `lite = "tabla"` o `lite = "figura"`.
