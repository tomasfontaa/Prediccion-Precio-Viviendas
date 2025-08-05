# Predicción-Precio-Viviendas - Proyecto Machine Learning

## 📌 Descripción del proyecto
Este proyecto predice precios de venta de viviendas utilizando técnicas de machine learning. Incluye preprocesamiento de datos, ingeniería de características y un modelo SVR optimizado que logra un RMSE de 0.172 (escala logarítmica).

## 📂 Estructura del Repositorio

- train_split.csv --> Datos de entrenamiento (1841 registros)
- test_kaggle.csv --> Datos de prueba (461 registros)
- submission.csv --> Predicciones del modelo
- prediccion_precios.ipynb --> Código completo del proyecto


## 🔧 Preprocesamiento de Datos

- Manejo de valores faltantes
- Transformación logarítmica
- Tratamiento de outliers
- Codificación de variables
- Selección de 13 características predictivas clave


## 🤖 Implementación del modelo

- Algoritmo: Support Vector Regression (SVR)
- Pipeline: MinMaxScaler --> SVR
- Rendimiento: RMSE = 0.172 (escala logarítmica)


## 🙌🏻 Autores

- Tomás Fonta
- Gonzalo Villar
- Carlos Sainz

## 📄 Licencia

MIT License – Siéntete libre de usarlo, modificarlo o adaptarlo con cariño 😄

