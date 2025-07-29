# 🧠 Predicción de riesgo de trastornos de salud mental a partir de factores sociales y laborales

**Autor:** Dulce Tapia
**Herramientas:** Pythom, GitHub  
**Fecha:** Julio 2025

## 📌 Descripción general del proyecto
Este proyecto tiene como objetivo predecir si una persona necesita tratamiento de salud mental utilizando variables sociales y del entorno laboral. Se emplea un dataset de encuestas aplicadas en el sector tecnológico. El análisis se enfoca en el preprocesamiento de datos, visualización, y entrenamiento de modelos de clasificación.

## 🎯 Objectivo
- Identificar factores asociados a la salud mental en el ámbito laboral.
- Desarrollar un modelo predictivo que detecte riesgo de trastornos mentales.
- Evaluar métricas de rendimiento del modelo como precisión, recall y F1-score.

## 🗃️ Dataset
- **Fuente:** Fuente: Mental Health in Tech Survey – Kaggle

## 🔧 Tools & Technologies
|Herramienta | Próposito                    |
|------------|------------------------------|
| **Python** | Limpieza de datos y análisis |
| **GitHub** | Control version & portfolio  |

## 🧪 Proceso de análisis
## 1. Carga y limpieza de datos
- Filtrado de edades no válidas.
- Estandarización de variables como género y entorno laboral.
- Tratamiento de valores nulos y codificación de variables categóricas.
## 2. Análisis exploratorio (EDA)
- Visualización de relaciones entre salud mental y variables como edad, género y ambiente de trabajo.
- Detección de patrones relevantes para modelado.
## 3. Modelado y predicción
- Clasificador usado: Random Forest
- Métricas obtenidas:
  -Accuracy: 72%
  -Recall para clase positiva (sí recibió tratamiento): 96%
  -Recall para clase negativa (no recibió tratamiento): 33%
Conclusión: el modelo es muy eficaz detectando a quienes sí necesitan tratamiento, pero menos efectivo con quienes no lo han recibido.
## 4. Interpretación
Las variables más influyentes fueron: work_interfere, family_history, Age, y benefits. 

## 📁 Project Structure
data/survey.csv

## 🚀 Cómo usar este repositorio
1. Clona el repositorio: git clone https://github.com/
2. Instala las dependencias: pip install -r requirements.txt
3. Abre el notebook y ejecuta cada celda paso a paso.
