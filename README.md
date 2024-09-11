# Predicción del Precio de Viviendas en California

Este repositorio contiene un análisis del dataset de precios de viviendas en California, con el objetivo de predecir el precio de una casa según sus características.

## Estructura del Proyecto

### Archivos

- **pregunta1.ipynb**: Notebook que responde a la primera pregunta del análisis: **¿Qué características influyen más en el valor de una casa?**
- **housing.csv**: Dataset que contiene las características de las casas y los precios.
- **README.md**: Este archivo, que proporciona una descripción general del proyecto.

## Preguntas Resueltas en el Notebook

### 1. ¿Qué características influyen más en el valor de una casa?

En este apartado, se construye un modelo de regresión lineal para predecir el precio de una casa. Se analizan los coeficientes del modelo entrenado para identificar las variables que tienen mayor impacto en el valor de las viviendas.

### 2. ¿Cuál es la precisión del algoritmo generado?

Aquí se evalúa la precisión del modelo de regresión utilizando el puntaje R². Este puntaje indica la proporción de la variabilidad en el precio de las casas que es explicada por las características incluidas en el modelo.

### 3. Métricas de evaluación del algoritmo

Se calculan y analizan las siguientes métricas para evaluar el rendimiento del modelo:

- **Error Absoluto Medio (MAE)**: Promedio de los errores absolutos entre las predicciones y los valores reales.
- **Error Cuadrático Medio (MSE)**: Promedio de los errores al cuadrado, que penaliza más los errores grandes.
- **Raíz del Error Cuadrático Medio (RMSE)**: Raíz cuadrada del MSE, proporciona una medida más interpretable del error.
- **Puntaje R²**: Proporción de la variabilidad en los datos que es explicada por el modelo.

**Interpretación de las métricas:**

- **MAE**: Indica, en promedio, cuánto se desvía la predicción del valor real.
- **MSE**: Penaliza fuertemente los errores grandes, lo que puede ser útil si estos son particularmente indeseables.
- **RMSE**: Similar al MSE pero en la misma unidad que la variable objetivo, facilitando su interpretación.
- **R²**: Un valor cercano a 1 indica que el modelo explica bien la variabilidad de los datos, mientras que un valor cercano a 0 sugiere lo contrario.

## Herramientas Utilizadas

- **Pandas**: Para la manipulación y análisis de los datos.
- **Scikit-learn**: Para la construcción y evaluación del modelo de regresión lineal.
- **NumPy**: Para operaciones numéricas.
