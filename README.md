# Factores de Riesgo Asociados a Enfermedad Cardíaca — BRFSS 2022

**Proyecto Final — Data Experience**

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Dataset](https://img.shields.io/badge/Dataset-CDC%20BRFSS%202022-green.svg)](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease)
[![License](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

---

## 📋 Descripción

Este proyecto implementa el ciclo completo de un proyecto de **Ciencia de Datos**: desde la búsqueda y limpieza de datos, hasta la construcción, evaluación e interpretación de modelos predictivos.

**Objetivo:** Analizar los factores demográficos, clínicos y conductuales asociados con la enfermedad cardíaca en la población adulta estadounidense, y construir un modelo capaz de predecir la probabilidad de que una persona haya experimentado enfermedad cardíaca.

**Fuente de datos:** Encuesta [BRFSS 2022](https://www.cdc.gov/brfss/) (Behavioral Risk Factor Surveillance System) del CDC, con ~445.000 registros y 40 variables.

---

## 📁 Estructura del Repositorio

```
.
├── README.md                                      # Este archivo
├── Informe_Proyecto_Final_DataExperience.docx   # Informe técnico completo en Word
├── Proyecto_Final_DataExperience.ipynb           # Notebook de Google Colab con código completo
├── Base_de_datos.csv                             # Dataset original (445.132 registros × 40 columnas)
│
└── (Datos intermedios generados durante la ejecución)
    ├── heart2022_limpio.csv                      # Dataset después de limpieza y preparación
    └── ... (otros archivos generados)
```

---

## 🎯 Objetivos Específicos

1. ✅ Limpiar, validar y preparar la base de datos siguiendo un ciclo ordenado de preprocesamiento
2. ✅ Caracterizar la muestra mediante análisis estadístico descriptivo
3. ✅ Explorar relaciones entre variables mediante EDA (Análisis Exploratorio de Datos)
4. ✅ Realizar pruebas estadísticas de hipótesis (Chi-cuadrado, Mann-Whitney U)
5. ✅ Entrenar y comparar modelos de clasificación (Regresión Logística, Random Forest)
6. ✅ Evaluar desempeño usando métricas apropiadas para datos desbalanceados
7. ✅ Interpretar factores de riesgo y formular recomendaciones

---

## 🚀 Inicio Rápido

### Requisitos

- Python 3.8+
- Librerías: pandas, numpy, scikit-learn, matplotlib, seaborn, scipy

### Instalación

```bash
# Clonar o descargar el repositorio
git clone <URL-DEL-REPOSITORIO>
cd <NOMBRE-CARPETA>

# Crear entorno virtual (opcional pero recomendado)
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate

# Instalar dependencias
pip install -r requirements.txt
# O instalar manualmente:
pip install pandas numpy scikit-learn matplotlib seaborn scipy jupyter
```

### Ejecutar el Notebook

Abre el notebook en Google Colab, Jupyter Notebook, o cualquier entorno compatible:

```bash
# Opción 1: Jupyter local    
jupyter notebook Proyecto_Final_DataExperience.ipynb

# Opción 2: Google Colab
# Sube el archivo a Colab y ejecuta las celdas en orden
```

---
