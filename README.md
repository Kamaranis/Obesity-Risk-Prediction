# Reto 4 | Práctica 2 - Tipología y Ciclo de Vida de los Datos
**TITULO**  
*Estimación de niveles de obesidad con base en los hábitos alimenticios y el estado físico*

Asignatura: M2.851 / Semestre: 2024-1 / Fecha: 7-12-2025

## Autor
  * Anton Barrera Mora - [abarreramora@uoc.edu](abarreramora@uoc.edu)

## Descripción del repositorio proyecto de análisis de obesidad con base en las variables de contexto:

Este repositorio contiene el código y los resultados del proyecto de análisis de obesidad realizado en R. El objetivo principal del proyecto es explorar la relación entre los hábitos alimenticios, la condición física y el nivel de obesidad, utilizando un conjunto de datos de la UCI Machine Learning Repository:  
https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition

**Contenido del repositorio:**

* **`Estimation of obesity levels based on eating... .Rmd`:** Archivo R Markdown que contiene el código y la documentación del análisis.
* **`Codigo`:** Carpeta que contiene el código en R utilizado para el análisis de datos.
* **`data`:** Carpeta que contiene los siguientes archivos:
    * **`dataset.csv`:** Conjunto de datos original, cargado directamente desde el archivo CSV proporcionado por la UCI Machine Learning Repository.
    * **`dataset_dirt.csv`:**  Conjunto de datos modificado, al que se le han introducido valores faltantes (`NA`) y celdas vacías ("") para probar las habilidades de imputación.
    * **`dataset_clean.csv`:** Conjunto de datos final, después de la imputación de valores faltantes y la limpieza de datos.
    * **`paper.pdf`:**  Paper redactado por los autores del conjunto de datos, que recoge detalles de su trabajo, la descripción de las variables y otra información relevante.
    * **`uci_dataset.zip`:** Archivo comprimido que contiene el conjunto de datos original y la documentación de la UCI Machine Learning Repository.
* **`LICENSE`:** Archivo de licencia del repositorio.
* **`README.md`:**  Este archivo, que contiene una descripción del proyecto y su contenido.
* **`.gitignore`:** Archivo que especifica los archivos y carpetas que Git debe ignorar.
* **`header.html`:** Archivo HTML que contiene el encabezado del documento R Markdown.
* **`variables.RData`:** Archivo RData que contiene las variables generadas durante el análisis.
**Descripción del proyecto:**

El proyecto se centra en el análisis de un conjunto de datos que contiene información sobre los hábitos alimenticios, la condición física y el nivel de obesidad de un grupo de individuos.  El análisis incluye:

* **Limpieza de datos:**  Imputación de valores faltantes y tratamiento de valores atípicos.
* **Análisis exploratorio:**  Visualización de la distribución de las variables y análisis de la relación entre variables.
* **Pruebas de hipótesis:**  Aplicación de pruebas estadísticas para comparar grupos y evaluar asociaciones entre variables.
* **Modelado:**  Construcción de un modelo de regresión ordinal para predecir el nivel de obesidad.

**Resultados:**

El análisis ha revelado asociaciones significativas entre el nivel de obesidad y diversas variables, como el consumo de alimentos altos en calorías, el historial familiar de sobrepeso, el tiempo de uso de dispositivos electrónicos y la frecuencia de actividad física.  El modelo de regresión ordinal ha mostrado un buen rendimiento en la predicción del nivel de obesidad.

**Instrucciones:**
Para replicar el análisis, se puede ejecutar el código en R contenido en el archivo "Estimation of obesity levels based on eating... .Rmd".  El conjunto de datos se encuentra en la carpeta "data". Se adjunta `variables.rdata` por si se considera necesario replicar el entorno

**Contribuciones:**

Las contribuciones al proyecto son bienvenidas.  Si encuentras algún error o tienes alguna sugerencia, por favor crea un "issue" o un "pull request" en el repositorio.
