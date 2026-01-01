# 🛠️ Predicción de Vida Útil Remanente (RUL) en flotas CAEX 

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

Este proyecto académico implementa un modelo de **Mantenimiento Predictivo** diseñado para estimar la **Remaining Useful Life (RUL)** de equipos críticos en entornos industriales. La capacidad de predecir la vida útil remanente permite pasar de un mantenimiento reactivo a uno proactivo, optimizando costos y seguridad.

## 📌 Contexto y Valor de Negocio
En operaciones de alta intensidad, la falla inesperada de un activo puede detener la producción. Este modelo analiza datos históricos de sensores para:
- Anticipar fallas catastróficas.
- Optimizar el stock de repuestos.
- Reducir el tiempo de inactividad no programado (Downtime).

## 🧪 Metodología Técnica
El flujo de trabajo incluye:
1. **Limpieza de Datos:** Tratamiento de valores atípicos (outliers) y normalización de señales de sensores.
2. **Ingeniería de Características:** Generación de medias móviles y tendencias temporales para capturar la degradación del equipo.
3. **Modelado:** Implementación de algoritmos de regresión para estimar el tiempo exacto hasta la falla.
4. **Evaluación:** Validación mediante métricas de error (RMSE / MAE).

## 📂 Estructura del Proyecto
- Datasets utilizados (muestras normalizadas).
- Análisis exploratorio y entrenamiento paso a paso.
- Funciones de preprocesamiento y predicción.
