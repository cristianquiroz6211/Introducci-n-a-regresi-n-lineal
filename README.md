# Introducción a Regresión Lineal: Predicción de Precios de Viviendas en Boston

## Descripción del Proyecto

Este repositorio contiene un proyecto de aprendizaje de **Machine Learning** enfocado en la **Regresión Lineal**. El objetivo principal es construir un modelo predictivo para estimar el valor medio de las viviendas en Boston, utilizando el conocido dataset `Boston Housing`.

Como estudiante, este proyecto ha sido mi primera inmersión práctica en el mundo de la regresión, con un enfoque particular en la **colaboración con herramientas de IA** para desglosar conceptos complejos y acelerar mi proceso de aprendizaje.

## Objetivo

El propósito de este proyecto es:
* Comprender los fundamentos de la Regresión Lineal.
* Realizar un análisis exploratorio de datos (EDA) para identificar las variables más influyentes.
* Entrenar y evaluar un modelo de regresión lineal simple.
* Aplicar un caso de uso práctico utilizando el dataset de Boston.

## Metodología

El `Jupyter Notebook` (`Regresion_lineal_pynb.ipynb`) documenta los siguientes pasos:

1.  **Carga y Exploración de Datos:** Se carga el dataset de Boston y se realiza una inspección inicial para entender su estructura y las 14 variables disponibles.
2.  **Análisis Exploratorio y Visualización:** Se utiliza un *heatmap* para visualizar la matriz de correlaciones y se identifican las variables `RM` (número medio de habitaciones por vivienda) y `LSTAT` (porcentaje de población de estatus inferior) como las más relevantes para predecir el valor de la vivienda (`MEDV`).
3.  **Preparación de los Datos:** Se seleccionan las variables predictoras y la variable objetivo para el entrenamiento del modelo.
4.  **Construcción y Entrenamiento del Modelo:** Se crea una instancia del modelo de regresión lineal de `scikit-learn` y se entrena con los datos seleccionados.
5.  **Evaluación del Modelo:** Se evalúa el desempeño del modelo con métricas básicas para entender su precisión predictiva.

## Tecnologías y Librerías

* **Python 3.x**
* **pandas**
* **NumPy**
* **scikit-learn**: Para el modelo de regresión lineal.
* **Matplotlib** y **seaborn**: Para la visualización de datos.

## Cómo Ejecutar el Proyecto

Para ejecutar este proyecto en tu entorno local, sigue estos pasos:

1.  Clona el repositorio:
    ```bash
    git clone [https://github.com/cristianquiroz6211/Introducci-n-a-regresi-n-lineal.git](https://github.com/cristianquiroz6211/Introducci-n-a-regresi-n-lineal.git)
    ```
2.  Navega al directorio del proyecto:
    ```bash
    cd Introducci-n-a-regresi-n-lineal
    ```
3.  Abre el `Jupyter Notebook` y ejecuta las celdas.

## Lecciones Aprendidas

Este proyecto me permitió comprender la importancia de:
* **La correlación entre variables:** Identificar relaciones clave antes de construir un modelo.
* **El poder de la IA como herramienta de apoyo:** Utilizar la IA para simplificar conceptos complejos y generar código base.
* **El flujo de trabajo completo de un proyecto de Machine Learning:** Desde la exploración de datos hasta la evaluación del modelo.

