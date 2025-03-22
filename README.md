# Proyecto de Análisis de Datos: Comparación de Modelos de Aprendizaje Automático

Este repositorio contiene un proyecto de análisis de datos que compara tres diferentes modelos de aprendizaje automático: regresión lineal, regresión logística y clasificación con árboles de decisión. El proyecto analiza diferentes conjuntos de datos utilizando estos modelos y evalúa su rendimiento.

## Estructura del Proyecto

### @data
El directorio `data` contiene los conjuntos de datos utilizados para entrenar y probar los modelos de aprendizaje automático:

- `linear_regression_data.csv`: Conjunto de datos de ventas de automóviles con características como año, kilómetros recorridos y precio de venta para la predicción de precios.
- `logistic_regression_data.csv`: Datos de salud con características relacionadas con condiciones cardíacas para clasificación binaria.
- `decision_tree_data.csv`: Conjunto de datos de calidad de vinos con propiedades fisicoquímicas para tareas de clasificación/regresión.

### @notebooks
El directorio `notebooks` contiene cuadernos Jupyter que implementan y documentan cada modelo:

- `linear_regression.ipynb`: Implementa un modelo de regresión lineal para predecir precios de venta de automóviles.
- `logistic_regression.ipynb`: Implementa un modelo de regresión logística para la clasificación de condiciones cardíacas.
- `decision_tree.ipynb`: Implementa un modelo de árbol de decisión para el análisis de la calidad del vino.

## Descripción del Análisis

Este proyecto realiza un análisis comparativo de tres algoritmos de aprendizaje automático en diferentes tipos de problemas:

1. **Regresión Lineal**: Predicción de valores continuos (precios de venta de automóviles) basados en diversas características.
2. **Regresión Logística**: Clasificación binaria de riesgo de condiciones cardíacas.
3. **Árbol de Decisión**: Clasificación y análisis de importancia de características para la calidad del vino.

Cada cuaderno contiene un pipeline de análisis completo que incluye:
- Carga y exploración de datos
- Preprocesamiento y limpieza de datos
- Ingeniería y selección de características
- Entrenamiento y optimización de modelos
- Evaluación del rendimiento y visualización
- Conclusión e interpretación

## Comenzando

Para reproducir este análisis:

1. Instalar las dependencias requeridas:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

2. Iniciar el servidor de Jupyter Notebook:
   ```
   jupyter notebook
   ```

3. Navegar al directorio de notebooks y abrir el cuaderno deseado.

## Resultados

El proyecto demuestra las fortalezas y debilidades de cada enfoque de modelado:

- **Regresión Lineal**: Funciona bien para predecir precios de automóviles, siendo los predictores clave el año, la marca y los kilómetros recorridos.
- **Regresión Logística**: Logra alta precisión en la clasificación de condiciones cardíacas, con características importantes que incluyen edad, tipo de dolor en el pecho y frecuencia cardíaca máxima.
- **Árbol de Decisión**: Proporciona buena interpretabilidad para la clasificación de la calidad del vino con un análisis detallado de la importancia de las características.