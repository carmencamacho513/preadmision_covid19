---
icon: chart-mixed
---

# Hito 1: Cálculo y Normalización del Exceso de Mortalidad

Para completar este hito de mi proyecto, necesito comprender a fondo dos conceptos fundamentales: el **exceso de mortalidad** y la **normalización de datos**. Estas dos herramientas son claves para realizar un análisis justo, comparativo y representativo entre países con realidades demográficas distintas.

## ¿Qué voy a hacer?

Mi objetivo será **calcular el promedio de muertes esperadas** durante el periodo de la pandemia, pero como si esta **no hubiera ocurrido**. Para lograrlo, trabajaré con datos históricos de los años anteriores a la pandemia y aplicaré la fórmula `AVERAGEIFS` (en español: `PROMEDIO.SI.CONJUNTO`) en Google Sheets. Esto me permitirá obtener un valor de referencia contra el cual comparar las cifras reales reportadas.

Con ese promedio, podré calcular el **exceso de muertes** al restar al número total de muertes reportadas durante la pandemia, el número promedio estimado en condiciones normales. Este exceso me ayudará a identificar si las cifras reportadas oficialmente como muertes por COVID-19 coinciden con el impacto real observado.

#### ¿Cómo haré comparaciones proporcionales entre países?

Dado que los países seleccionados (Chile, Colombia, México y Perú) tienen poblaciones de tamaños diferentes, es esencial **normalizar los datos**. Para ello, calcularé las muertes (tanto las reportadas por COVID-19 como el exceso de mortalidad) **por cada 100,000 habitantes**. Esto permitirá una comparación proporcional y justa del impacto de la pandemia entre países.

#### Visualización y análisis

Para facilitar el análisis, crearé:

* **Gráficos de líneas por país**, donde mostraré la evolución semanal o mensual del número de muertes reportadas y el exceso de muertes, ambos normalizados.
* **Gráficos acumulados**, para observar tendencias a lo largo del tiempo.
* **Tablas resumen**, usando fórmulas y tablas dinámicas.
* Un **gráfico de barras comparativo**, con los resultados generales de cada país.

#### Dashboard y presentación

Una vez tenga todos los resultados, diseñaré un **panel de control (dashboard)** en una hoja nueva de Google Sheets. Este tablero mostrará de forma clara y visual los datos más importantes, incluyendo:

* Muertes esperadas
* Muertes reportadas
* Exceso de muertes
* Muertes por COVID-19 reportadas
* Cifras por cada 100,000 habitantes

Además, crearé una **presentación en slides** que me servirá como guía para explicar mi análisis, hallazgos y conclusiones.

####

***
