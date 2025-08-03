# README: Análisis de predicción de cancelaciones en Telecom X

## 📌 Descripción del Proyecto
El análisis incluye:

- Preparación y limpieza de datos
- Ingeniería de características
- Modelado con algoritmos de machine learning
- Evaluación de rendimiento
- Interpretación de resultados para generar insights accionables

## 🔍 Objetivos Principales
1. Predecir qué clientes tienen mayor riesgo de churn
2. Identificar los factores más influyentes en la decisión de cancelación
3. Proponer estrategias de retención basadas en datos

## 📊 Métodos Utilizados
- **Preprocesamiento**: Encoding categórico, normalización, balanceo de clases (SMOTE)
- **Modelado**: Regresión Logística y Random Forest
- **Evaluación**: Exactitud, Precisión, Recall, F1-score, Matriz de Confusión
- **Análisis**: Importancia de variables, correlaciones, visualizaciones

## 📂 Estructura del Código
1. Preparación de datos (eliminación de columnas, encoding)
2. Análisis exploratorio (distribución de churn, correlaciones)
3. Balanceo y normalización
4. Modelado predictivo
5. Evaluación e interpretación de resultados

## 💡 Principales Hallazgos
- **Factores clave de churn**: Tiempo como cliente, tipo de contrato, cargos mensuales
- **Servicios protectores**: Online Security y Tech Support reducen churn
- **Modelo óptimo**: Random Forest (F1-score: 0.92)

## 🚀 Recomendaciones Estratégicas
- Programas de retención para nuevos clientes
- Incentivos para contratos a largo plazo
- Promoción de servicios de valor agregado
- Sistema de alerta temprana para clientes de riesgo

## 🛠️ Tecnologías Utilizadas
- Python (pandas, numpy, scikit-learn)
- Jupyter Notebook
- Bibliotecas de visualización (matplotlib, seaborn)
