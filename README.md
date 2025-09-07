# Predicción de Enfermedad Coronaria a 10 Años

## Introducción

Este proyecto tiene como objetivo aplicar técnicas de **Machine Learning (ML)** y **Deep Learning (DL)** para predecir la probabilidad de desarrollar enfermedad coronaria (CHD) a 10 años, utilizando el dataset **Framingham Heart Study**.  

Se realiza un análisis completo de los datos, seguido del entrenamiento y evaluación de distintos modelos supervisados. Además, se generan predicciones sobre pacientes hipotéticos para demostrar la capacidad predictiva del modelo seleccionado.

## Contenido del proyecto

- **Análisis Exploratorio de Datos (EDA)**: limpieza de datos, visualización de distribuciones y correlaciones.
- **Preprocesamiento de datos**: normalización y tratamiento de variables numéricas y categóricas.
- **Modelos entrenados**:
  1. k-Nearest Neighbors (kNN)
  2. Random Forest
  3. Gradient Boosting
  4. Deep Neural Network (DNN)
- **Evaluación y comparación de modelos**: accuracy en Train, Validation y Test.
- **Predicción de muestras artificiales**: ejemplos de perfiles de pacientes inventados.
- **Estrategias de validación cruzada**: K-Fold y LOOCV.
- **Conclusiones generales**: desempeño de modelos y recomendaciones.

## Requisitos

- Python 3.8+
- Pandas, NumPy, Matplotlib, Seaborn
- scikit-learn
- TensorFlow / Keras

## Uso

1. Cargar el dataset `framingham.csv`.  
2. Ejecutar los scripts de preprocesamiento y análisis.  
3. Entrenar los modelos y generar resultados comparativos.  
4. Generar predicciones sobre nuevas muestras.

