# Repositorio para calcular Tabulados de la ENVIPE
![Estatus](https://img.shields.io/badge/Estatus-desarrollo-yellow)

## Introducción

En este repositorio encuentras código en R para realizar el cálculo de algunos tabulados básicos de la encuesta ENVIPE.


## Acerca de este proyecto

La Encuesta Nacional de Victimización y Percepción sobre Seguridad Pública (ENVIPE) 2024 es la décima cuarta entrega de la serie estadística generada por el Subsistema Nacional de Información de Gobierno, Seguridad Pública e Impartición de Justicia (SNIGSPIJ), coordinada por el Instituto Nacional de Estadística y Geografía (INEGI). Con este proyecto se da continuidad a las temáticas abordadas en las ediciones anteriores de esta encuesta, cuyos resultados han sido declarados Información de Interés Nacional por la Junta de Gobierno del INEGI.

Para mayor información y descarga de datos, cuestionarios, etcétera visite el enlace: [ENVIPE 2024](https://www.inegi.org.mx/programas/envipe/2024/)



## Requerimientos
- [R (> 4.0)](https://www.r-project.org/)
- [Quarto](https://quarto.org/)  

Se recomienda instalar el IDE [Rstudio](https://www.rstudio.com/categories/rstudio-ide/), sin embargo es posible correr este proyecto con cualquier otro IDE donde la persona usuaria pueda utilizar `R`.

También puedes encontrar este proyecto listo para usarse en `posit cloud` en este [Enlace](https://posit.cloud/content/9475266)

## Instrucciones de uso

Para ejecutar el código en este repositorio es necesario tener instalado el lenguaje de programación estadística `R`. El repositorio está ordenado de tal forma que todos los códigos se encuentran en la carpeta `procesamiento` y los datos se almacenan en la carpeta `datos`.

Si lo vas a utilizar en tu equipo local el primer paso es descargar los datos de la ENVIPE [Datos](https://www.inegi.org.mx/programas/envipe/2024/#microdatos) del portal del INEGI, descomprime y pega las tablas csv en la carpeta `datos-originales`. Renderiza el archivo que necesites, por ejemplo `total-victimas.qmd` para obtener un `Html con los resultados`. Si lo corres desde posit cloud simplemente renderiza, ya te dejé los datos.

Enjoy!