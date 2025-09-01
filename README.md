# TFG - Aplicación de técnicas de aprendizaje automático sobre datos con muestreo irregular

Este proyecto forma parte de mi **Trabajo de Fin de Grado en Matemáticas**.  
El objetivo es predecir la **presión transmembrana (TMP)** en un sistema de **biorreactor de membrana (MBR)**, un parámetro crítico en el tratamiento de aguas residuales.  
El dataset presenta **series temporales irregulares**, lo que plantea un reto adicional para los modelos tradicionales de machine learning.

---

## ⚙️ Tecnologías utilizadas
- **Python**: pandas, numpy, matplotlib, seaborn, scikit-learn, TensorFlow/Keras

---

## 📊 Pipeline del proyecto:
El estudio a nivel técnico está realizado en dos notebooks: dataset y modelos

1. **Dataset**  
   - Descarga de datos  
   - Análisis inical y correlaciones
   - Dettección de irregularidades, ingeniería de variables y tratamiento de estas
   - Dettección y tratamiento de outliers
   - Gráficos de interés

2. **Modelos**  
   - Random Forest (baseline robusto)  
   - MLP (red neuronal feed-forward)  
   - LSTM Time-Aware (secuencias irregulares)
   - Evaluación
---
