# 📈 AluraTelecomX2Latam - Análisis de Cancelación de Clientes

## 🔍 Introducción

Este proyecto aborda la problemática de cancelación de clientes (churn) en Telecom X, una empresa de telecomunicaciones con alta rotación de usuarios. El objetivo principal es identificar los factores que influyen en la cancelación y construir modelos predictivos que permitan anticipar el abandono, mejorando así la retención.

## 🎯 Objetivos

- Identificar los principales factores que conducen al churn.
- Construir modelos predictivos para anticipar cancelaciones.
- Proponer estrategias comerciales basadas en los hallazgos.
- Optimizar la experiencia del cliente y reducir el churn.

## 🧠 Metodología

El análisis se desarrolló en Python utilizando técnicas de ciencia de datos:

- **Limpieza y transformación de datos**: Eliminación de columnas irrelevantes y codificación de variables.
- **Visualización**: Boxplots, gráficos de correlación y proporciones de cancelación.
- **Modelado predictivo**: Se entrenaron tres modelos:
  - Logistic Regression (LR)
  - Random Forest (RF)
  - Gradient Boosting Machine (GBM)
- **Modelo híbrido**: Se utilizó un VotingClassifier para combinar RF y GBM y mejorar el rendimiento.
- **Evaluación**: Métricas como Accuracy, Precision, Recall y F1 Score.

## 📊 Principales Hallazgos

- **Duración del contrato**: A mayor duración, menor probabilidad de cancelación.
- **Tipo de contrato**: Los contratos “Mes a Mes” tienen mayor riesgo de churn.
- **Método de pago**: El uso de cheque electrónico se asocia con mayor abandono.
- **Servicio de fibra óptica**: Sorprendentemente, se vincula con mayor riesgo de cancelación.
- **Cargos mensuales**: Su impacto depende del contexto contractual.

## 🛠️ Herramientas Utilizadas

- Python (Pandas, Seaborn, Scikit-learn, Imbalanced-learn, Plotly)
- Google Colab
- GitHub para control de versiones

## 📌 Recomendaciones

1. Migrar clientes de contratos “Mes a Mes” a planes más largos con incentivos.
2. Promover métodos de pago automáticos para reducir fricción.
3. Auditar el servicio de fibra óptica y revisar expectativas vs. experiencia.
4. Usar el modelo predictivo para segmentar clientes con alto riesgo.

## 📁 Estructura del Proyecto

