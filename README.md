# Predicting Optimal Fertilizers - Kaggle Competition

Este proyecto participa en una competencia de Kaggle con el objetivo de predecir el fertilizante óptimo para distintos cultivos, basándose en parámetros de suelo y clima.

## 📌 Objetivo

Usar técnicas de Machine Learning para predecir el tipo de fertilizante más adecuado para una combinación de condiciones agrícolas dadas.

## 📂 Estructura del Proyecto

- `Predicting_Optimal_Fertilizers_Kraggle_Competition.ipynb`: Notebook principal con todo el pipeline de desarrollo, desde el análisis exploratorio hasta la predicción final.
- `fertilizer.csv`: Dataset utilizado (cargado desde Kaggle o entregado por la competencia).
- `submission.csv`: Archivo generado para enviar predicciones a la competencia.

## 🔍 Técnicas Usadas

- Limpieza de datos
- Análisis exploratorio de datos (EDA)
- Codificación de variables categóricas
- Modelos de clasificación:
  - Random Forest
  - XGBoost
- Métricas de evaluación: Accuracy, Confusion Matrix

## 🛠️ Requisitos

- Python 3.x
- Bibliotecas:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - xgboost

Instalación rápida:

```bash
pip install -r requirements.txt
```

## 📊 Resultados
Se logró una precisión razonable en las predicciones. Se aplicaron diferentes técnicas de codificación y validación cruzada para optimizar el modelo final.

## 🤝 Contribuciones
Proyecto personal con fines educativos y para la competencia de Kaggle.
