# 📉 Scoring de Riesgo Crediticio - Lending Club

Este proyecto consiste en un pipeline completo de Machine Learning diseñado para predecir la probabilidad de impago (default) de los solicitantes de préstamos de la plataforma Lending Club.

## 🚀 Descripción del Proyecto
El objetivo es transformar datos financieros históricos en una herramienta de decisión capaz de clasificar si un crédito debe ser aprobado o rechazado basándose en una probabilidad de riesgo calculada mediante XGBoost.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python 3.12
* **Procesamiento de Datos:** Pandas, Numpy
* **Machine Learning:** XGBoost (Implementación con aceleración por GPU/CUDA)
* **Visualización:** Matplotlib, Seaborn
* **Entorno:** Google Colab

## 📊 Características del Modelo
* **Pipeline de Datos:** Limpieza robusta, manejo de valores nulos y codificación One-Hot para variables categóricas.
* **Ingeniería de Características:** Creación de métricas financieras clave (carga financiera, proporción de préstamo vs ingreso).
* **Entrenamiento optimizado:** Uso de `Early Stopping` para evitar el sobreajuste (overfitting) y balanceo de clases para manejar la naturaleza desigual de los datos de riesgo.
* **Simulador de Crédito:** Función integrada para realizar predicciones "en tiempo real" con nuevos datos de clientes.

## 📁 Estructura del Notebook
1. **Limpieza:** Tratamiento de tipos de datos, ingeniería de variables y limpieza de nombres de columnas.
2. **Entrenamiento:** Configuración del clasificador XGBoost con parámetros ajustados.
3. **Evaluación:** Reportes de clasificación, Matriz de Confusión y análisis de importancia de variables.
4. **Simulador:** Función `simular_cliente` para inferencia rápida.

## 📈 Resultados
El modelo logra una capacidad predictiva sólida, permitiendo identificar patrones de riesgo de manera eficiente y escalable.

---
*Desarrollado por: [Tu Nombre]*
