---
title: "Recursos académicos"
format:
  html:
    toc: true
    toc-expand: false
    code-fold: false
    collapse-sections: true
    collapse-open: false
---


::: {.cell}

:::


En esta sección encontrará recursos académicos organizados en pestañas para facilitar su consulta. Incluyen materiales sobre visualización de datos, simulaciones interactivas y herramientas útiles para cursos de probabilidad, estadística e ingeniería.

Todo el material, exceptuando aquel etiquetado como externo, es de mi autoría.


## Infografías `<svg aria-hidden="true" role="img" viewBox="0 0 640 512" style="height:1em;width:1.25em;vertical-align:-0.125em;margin-left:auto;margin-right:auto;font-size:inherit;fill:currentColor;overflow:visible;position:relative;"><path d="M160 64c0-35.3 28.7-64 64-64H576c35.3 0 64 28.7 64 64V352c0 35.3-28.7 64-64 64H336.8c-11.8-25.5-29.9-47.5-52.4-64H384V320c0-17.7 14.3-32 32-32h64c17.7 0 32 14.3 32 32v32h64V64L224 64v49.1C205.2 102.2 183.3 96 160 96V64zm0 64a96 96 0 1 1 0 192 96 96 0 1 1 0-192zM133.3 352h53.3C260.3 352 320 411.7 320 485.3c0 14.7-11.9 26.7-26.7 26.7H26.7C11.9 512 0 500.1 0 485.3C0 411.7 59.7 352 133.3 352z"/></svg>`{=html}

* [Comprendiendo los valores P](docencia/Comprendiendo el valor P.pdf){target="_blank"} 

Esta infografía presenta la definición del valor P, criterios para su interpretación y una guía para la elección del nivel de significancia ($\alpha$). 


## Simulaciones y visualizaciones interactivas `<svg aria-hidden="true" role="img" viewBox="0 0 384 512" style="height:1em;width:0.75em;vertical-align:-0.125em;margin-left:auto;margin-right:auto;font-size:inherit;fill:currentColor;overflow:visible;position:relative;"><path d="M64 0C28.7 0 0 28.7 0 64V448c0 35.3 28.7 64 64 64H320c35.3 0 64-28.7 64-64V64c0-35.3-28.7-64-64-64H64zM96 64H288c17.7 0 32 14.3 32 32v32c0 17.7-14.3 32-32 32H96c-17.7 0-32-14.3-32-32V96c0-17.7 14.3-32 32-32zm32 160a32 32 0 1 1 -64 0 32 32 0 1 1 64 0zM96 352a32 32 0 1 1 0-64 32 32 0 1 1 0 64zM64 416c0-17.7 14.3-32 32-32h96c17.7 0 32 14.3 32 32s-14.3 32-32 32H96c-17.7 0-32-14.3-32-32zM192 256a32 32 0 1 1 0-64 32 32 0 1 1 0 64zm32 64a32 32 0 1 1 -64 0 32 32 0 1 1 64 0zm64-64a32 32 0 1 1 0-64 32 32 0 1 1 0 64zm32 64a32 32 0 1 1 -64 0 32 32 0 1 1 64 0zM288 448a32 32 0 1 1 0-64 32 32 0 1 1 0 64z"/></svg>`{=html}

* [Distribuciones discretas interactivas](docencia/distribuciones-discretas.html){target="_blank"}

Este visualizador le permite explorar las principales distribuciones discretas y ver como cambian sus formas al modificar los parámetros. 

* [Distribuciones continuas interactivas](docencia/distribuciones-continuas.html){target="_blank"}

Es el equivalente continuo al visualizador anterior, pero además, presenta una comparación entre la distribución normal estándar ($z$) y la t-Student ($t$).

* [Curvas OC para muestreo por atributos](docencia/curvas-oc.html){target="_blank"}

Propio del campo de la ingeniería de calidad y muestreo de aceptación, este visualizador muestra las curvas características de operación (OC) de planes de muestreo por atributos.

* [Efecto de la asimetría sobre el TLC](https://rpubs.com/SGGoni){target="_blank"}

Inspirado en algunas publicaciones científicas, aquí podrá encontrar como la asimetría juega un papel ponderante en el cumplimiento del teorema del límite central (TLC). Con este, busco ayudar a "derrumbar" el mito de que el TLC siempre se cumple con $n=30$.

* [Calculadora de distribuciones de probabilidad e intervalos de confianza](https://homepage.divms.uiowa.edu/~mbognar/){target="_blank"} - Aplicación externa

De Ph.D. Matt Bognar, aquí encuentra "mini aplicaciones" con las que puede resolver ejercicios de probabilidad y estadística.

* [Ley de los Grandes Números](https://www.geogebra.org/m/edy5fexu){target="_blank"}  - Aplicación externa

Es una explicación de Rafael Pérez Laserna sobre la Ley de los Grandes Números, que incluye una simulación de un dado que nos ayuda a comprenderla. 

* [Teorema del Límite Central (TLC)](https://seeing-theory.brown.edu/probability-distributions/es.html#section3){target="_blank"}  - Aplicación externa

Uno de los pilares de la estadística frecuentista, este enlace muestra una simulación del TLC que nos permite comprender el TLC de mejor forma. 

* Aplicación interactiva sobre los intervalos de confianza

Este es un gist que al ejecutarse en R con sus respectivas librerías, despliega una aplicación local que permite comprender mejor el funcionamiento de los intervalos de confianza y como estos dependen del estimador puntual (aleatorio por el muestreo), el tamaño de muestra y el nivel de confianza seleccionado. 


::: {.cell}

```{.r .cell-code}
# Correr en R (requiere shiny y tidyverse)

library(shiny)
library(tidyverse)

runGist("d47f4c205b531e3bed59d22b22cbfd13")
```
:::


## Recursos para la construcción de gráficos `<svg aria-hidden="true" role="img" viewBox="0 0 448 512" style="height:1em;width:0.88em;vertical-align:-0.125em;margin-left:auto;margin-right:auto;font-size:inherit;fill:currentColor;overflow:visible;position:relative;"><path d="M160 80c0-26.5 21.5-48 48-48h32c26.5 0 48 21.5 48 48V432c0 26.5-21.5 48-48 48H208c-26.5 0-48-21.5-48-48V80zM0 272c0-26.5 21.5-48 48-48H80c26.5 0 48 21.5 48 48V432c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V272zM368 96h32c26.5 0 48 21.5 48 48V432c0 26.5-21.5 48-48 48H368c-26.5 0-48-21.5-48-48V144c0-26.5 21.5-48 48-48z"/></svg>`{=html}

* [Seleccione el gráfico adecuado](https://www.data-to-viz.com/#explore){target="_blank"}

¿Qué tipo de datos tiene? Elija el tipo principal usando esta guía.

* [Evite estos errores](https://www.data-to-viz.com/caveats.html){target="_blank"}

Una colección de advertencias para la visualización de datos

* [Otro catálogo de visualización de datos](https://datavizcatalogue.com/ES/){target="_blank"}

Encuentre otros gráficos y guías para su construcción.

## Tutoriales en `<svg aria-hidden="true" role="img" viewBox="0 0 581 512" style="height:1em;width:1.13em;vertical-align:-0.125em;margin-left:auto;margin-right:auto;font-size:inherit;fill:currentColor;overflow:visible;position:relative;"><path d="M581 226.6C581 119.1 450.9 32 290.5 32S0 119.1 0 226.6C0 322.4 103.3 402 239.4 418.1V480h99.1v-61.5c24.3-2.7 47.6-7.4 69.4-13.9L448 480h112l-67.4-113.7c54.5-35.4 88.4-84.9 88.4-139.7zm-466.8 14.5c0-73.5 98.9-133 220.8-133s211.9 40.7 211.9 133c0 50.1-26.5 85-70.3 106.4-2.4-1.6-4.7-2.9-6.4-3.7-10.2-5.2-27.8-10.5-27.8-10.5s86.6-6.4 86.6-92.7-90.6-87.9-90.6-87.9h-199V361c-74.1-21.5-125.2-67.1-125.2-119.9zm225.1 38.3v-55.6c57.8 0 87.8-6.8 87.8 27.3 0 36.5-38.2 28.3-87.8 28.3zm-.9 72.5H365c10.8 0 18.9 11.7 24 19.2-16.1 1.9-33 2.8-50.6 2.9v-22.1z"/></svg>`{=html}

### Aspectos generales

### Estadística

### Ingeniería de Calidad

* [Diagrama de Pareto](docencia/diagrama_pareto.html){target="_blank"} 

Aprenda a realizar un gráfico de Pareto en R. Este es un principio que dice que una pequeña cantidad de causas suele explicar la mayor parte de los efectos

* [Gráficos de control para variables](docencia/graficos_control.html){target="_blank"}

Los gráficos de control son herramientas estadísticas. Su uso es la forma más eficaz de distinguir entre causa común y atribuible para la variabilidad cuando se supervisa el resultado del proceso en tiempo real. 

* [Gráficos de control para atributos](docencia/graficos_control_atributos.html){target="_blank"}

Mientras que los gráficos de control para variables rastrean las cantidades medidas relacionadas con la calidad de los resultados del proceso, los gráficos para atributos siguen el recuento de los elementos no conformes.

* [Análisis de capacidad para datos normales](docencia/capacidad_datos_normales.html){target="_blank"}

Un análisis de capacidad es una herramienta estadística que evalúa si un proceso puede cumplir de forma consistente con los requisitos o especificaciones establecidos. Compara la variabilidad natural del proceso con los límites de tolerancia del cliente para determinar qué tan capaz es.

* [Análisis de capacidad para datos no normales](docencia/capacidad_datos_no_normales.html){target="_blank"}

Es relativamente común encontrarse con procesos que no siguen la distribución normal, ya sea por que así es como debe comportarse o bien, por errores que suceden a la hora de recolectar, almacenar o procesar los datos. 
