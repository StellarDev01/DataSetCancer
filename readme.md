

# 🧠 Clasificación de Tumores con Redes Neuronales

## 🎯 Objetivo

Diseñar e implementar un modelo de **red neuronal de propagación hacia adelante** que, a partir de las características de un tumor, permita predecir si es **benigno (B)** o **maligno (M)**. El modelo trabajará sobre un conjunto de datos reales sobre cáncer de mama: `DataSet_Cancer.csv`.

---

## 📊 Descripción del Dataset

El dataset incluye diversas características extraídas de imágenes médicas. Algunas de las variables más relevantes son:

- `radio_promedio`, `perímetro_promedio`, `área_promedio`
- `concavidad_promedio`, `simetría_promedio`, `dimensión_fractal_promedio`
- Sus respectivas métricas de error estándar (`error_estándar_*`)
- Y los valores máximos o "peores" para cada característica (`peor_*`)

El campo objetivo es:  
**`diagnóstico`**:  
- `B` → Benigno  
- `M` → Maligno

---

## 🧪 Requerimientos del Proyecto

### 1. Análisis Exploratorio de Datos (EDA)

- Limpieza de datos, transformación de variables y visualización.
- Toda decisión tomada debe ser **justificada**.

### 2. Modelo de Red Neuronal

- Implementar una red neuronal con **precisión ≥ 80%**
- División del dataset:
  - **70% Entrenamiento**
  - **20% Validación**
  - **10% Prueba**
- Documentar y justificar:
  - Hiperparámetros del modelo final
  - Curvas de aprendizaje
- Mostrar las curvas de aprendizaje de los modelos previos.

### 3. Evaluación y Comparación

- Registrar precisión y pruebas del modelo final.
- Comparar el modelo final con al menos un modelo anterior usando:
  - Curvas de aprendizaje
  - Métricas clave
  - Visualizaciones con interpretación

---
