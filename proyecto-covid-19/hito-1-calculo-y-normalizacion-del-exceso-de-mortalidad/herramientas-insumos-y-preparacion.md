---
icon: magnifying-glass-waveform
---

# Herramientas, Insumos y Preparación

### Herramientas y/o plataformas

Para desarrollar este proyecto, **utilizaré dos herramientas principales de Google**, ambas gratuitas, accesibles desde la nube y muy útiles para el trabajo colaborativo:

* **Google Sheets**, donde realizaré todo el análisis de datos, incluyendo limpieza, cálculos, visualizaciones y creación del dashboard.
* **Google Presentations**, donde construiré una presentación clara y concisa para exponer mis hallazgos y conclusiones al final del proyecto.

Estas herramientas me permitirán organizar el trabajo de manera eficiente y mantener toda la información disponible en línea.

### Lenguajes

En este proyecto **no utilizaré ningún lenguaje de programación**, sino que trabajaré exclusivamente con **fórmulas propias de Google Sheets**. Esto incluirá funciones como:

* `AVERAGEIFS` (`PROMEDIO.SI.CONJUNTO`)
* `SUMIFS`
* `FILTER`
* `ARRAYFORMULA`
* entre otras, que aplicaré para hacer cálculos automáticos, análisis comparativos y normalización de datos.

### Insumos

Trabajaré a partir de un archivo base de **Google Sheets** "[Proyecto Covid-19](https://docs.google.com/spreadsheets/d/1H5r-eY_95bYatrzBo0HJ0V-UwXzlVA4noIn66tx1Pro/edit?gid=126190557#gid=126190557)". Este archivo contiene **dos hojas** (también llamadas “pestañas”), con la información fundamental para el análisis:

**Hoja "dataset"**

Contiene **1,252 filas**, cada una representando los datos acumulados **por semana** para cada país. Las columnas disponibles en esta hoja son:

* **país**: Nombre del país (puede ser México, Perú, Chile o Colombia).
* **fecha inicio**: Fecha de inicio de la semana correspondiente.
* **fecha fin**: Fecha de cierre de la semana.
* **semana**: Número de la semana del año (de la 1 a la 52).
* **total muertes reportadas**: Total de muertes registradas por cualquier causa en ese rango semanal.
* **total muertes reportadas por COVID específicamente**: Total de muertes atribuidas directamente al COVID-19 durante esa misma semana.

**Hoja "poblacion"**

Contiene la **población total de cada uno de los cuatro países** analizados. Esta información será fundamental para poder **normalizar los datos** y calcular tasas proporcionales por cada 100,000 habitantes, lo que me permitirá hacer comparaciones justas entre países con tamaños poblacionales diferentes.

***
