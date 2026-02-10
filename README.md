# CHALLENGE_TELECOMX-2
Proyecto de Machine Learning para la predicción de churn en una empresa de telecomunicaciones. Incluye preparación de datos, análisis exploratorio, entrenamiento y evaluación de modelos de clasificación, y análisis de importancia de variables, con foco en la interpretación y el impacto estratégico en el negocio.

----

# Telecom X – Predicción de Cancelación de Clientes (Churn)

## 📌 Descripción del proyecto
Este proyecto aborda el problema de **cancelación de clientes (churn)** en una empresa de telecomunicaciones ficticia llamada *Telecom X*.  
El objetivo es **desarrollar modelos de Machine Learning capaces de predecir qué clientes tienen mayor probabilidad de cancelar sus servicios**, permitiendo a la empresa anticiparse y diseñar estrategias de retención.

El proyecto cubre **todo el pipeline de ciencia de datos**, desde la preparación de los datos hasta la evaluación e interpretación de modelos predictivos.

---

## 🎯 Objetivos
- Preparar y transformar los datos para su uso en modelos de Machine Learning.
- Analizar la relación entre variables y la cancelación de clientes.
- Entrenar y comparar distintos modelos de clasificación.
- Evaluar el desempeño de los modelos con métricas estándar.
- Interpretar la importancia de las variables y extraer insights estratégicos.

---

## 🧠 Metodología

### 1. Preparación de datos
- Uso de un dataset previamente limpiado (Parte 1 del challenge).
- Eliminación de variables irrelevantes.
- Codificación de variables categóricas (One-Hot Encoding).
- Separación de datos en entrenamiento y prueba.
- Imputación de valores faltantes.
- Normalización aplicada solo a modelos sensibles a la escala.

### 2. Análisis exploratorio dirigido
- Análisis de la distribución de la variable objetivo (churn).
- Visualización de relaciones entre variables clave y la cancelación.
- Identificación de patrones relevantes para el modelado.

### 3. Modelado predictivo
Se entrenaron y compararon los siguientes modelos:
- **Dummy Classifier** (baseline)
- **Regresión Logística** (con normalización)
- **Random Forest** (sin normalización)

### 4. Evaluación de modelos
Los modelos fueron evaluados utilizando:
- Accuracy
- Precision
- Recall
- F1-score
- Matriz de confusión

El análisis se enfocó especialmente en la clase *churn*, por su importancia estratégica.

### 5. Importancia de variables
- Regresión Logística: análisis de coeficientes.
- Random Forest: análisis de importancia de variables.
- Comparación de resultados para identificar factores clave de cancelación.

---

## 📊 Resultados principales
- La **Regresión Logística** mostró un mejor equilibrio entre desempeño e interpretabilidad, destacando en la detección de clientes con riesgo de cancelación.
- Variables como **antigüedad del cliente (tenure)**, **cargos mensuales** y **tipo de contrato** fueron identificadas como factores clave en la predicción del churn.
- El enfoque permitió priorizar la detección de clientes en riesgo por sobre la simple maximización de la exactitud global.

---

## 🛠️ Tecnologías utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## 📂 Estructura del repositorio
- `*.ipynb` – Notebook principal con todo el desarrollo del proyecto.
- `telecomx_limpio.csv` – Dataset preprocesado utilizado para el modelado (opcional).
- `README.md` – Documentación del proyecto.

---

## 📚 Contexto
Proyecto desarrollado como parte del programa **Oracle ONE / Alura Latam**, enfocado en la aplicación práctica de Machine Learning, buenas prácticas de modelado y comunicación de resultados con impacto en el negocio.

---

## 🚀 Autor
Proyecto desarrollado con fines educativos y de portafolio en Ciencia de Datos y Machine Learning.

