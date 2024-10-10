# Imputación Robusta en Series Temporales - Metro de Medellín

Este repositorio contiene el código y los análisis del proyecto de imputación robusta de datos faltantes en series temporales de afluencia del Metro de Medellín. Se comparan métodos tradicionales y robustos de regresión para abordar la influencia de valores atípicos y mejorar la precisión de las imputaciones.

## Descripción del Proyecto

El objetivo principal es evaluar la efectividad de modelos de regresión robusta (RLM, RANSAC) comparados con la regresión lineal tradicional para la imputación de datos faltantes en series temporales con outliers. El proyecto sigue el marco CRISP-DM, desde la preparación de datos hasta la evaluación de modelos con métricas como MAPE y MdAPE.

### Componentes Principales:
- **Modelos de Regresión**: Comparación de Regresión Lineal, RLM (Modelos Lineales Robustos) y RANSAC.
- **Imputación de Datos Faltantes**: Imputación en series temporales con datos contaminados por valores atípicos.
- **Pruebas Estadísticas**: Test de Wilcoxon para evaluar diferencias significativas entre modelos.
