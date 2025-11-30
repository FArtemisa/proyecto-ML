## Sistema de Predicción de PCOS. Proyecto de Machine Learning y Matemáticas
Este repositorio contiene un proyecto de análisis y modelado supervisado orientado a la predicción del Síndrome de Ovario Poliquístico (PCOS). Incluye procesamiento exploratorio de datos, imputación, selección/normalización de variables, entrenamiento y comparación de varios algoritmos de clasificación (Random Forest, Árbol de Decisión, Regresión Logística y SVM), búsqueda de hiperparámetros mediante GridSearchCV,
validación cruzada y visualizaciones explicativas.

El propósito es presentar un flujo completo de trabajo reproducible para clasificación binaria en contexto biomédico, extraer conclusiones sobre desempeño y variables más relevantes, y facilitar la extensión y experimentación posterior.

---

## Autoras
Iris Alina Pérez Rivera
Fernanda García Rodríguez
Diana García Trujillo
Karol Paola Rosales Miranda

---

## Contexto del Problema y justificacion
El Síndrome de Ovario Poliquístico (PCOS) es una condición endocrina que afecta 
aproximadamente al 10% de las mujeres en edad reproductiva a nivel mundial. Se 
caracteriza por desequilibrios hormonales, quistes ováricos y diversos síntomas 
metabólicos. El diagnóstico temprano es crucial para prevenir complicaciones a 
largo plazo como diabetes tipo 2, enfermedades cardiovasculares e infertilidad.

La implementación de modelos predictivos para el diagnóstico de PCOS resulta 
fundamental para complementar la labor médica, agilizando el proceso de 
detección mediante el análisis automatizado de variables clínicas y hormonales. 
Así mismo, estos modelos no solo asisten a los profesionales de la salud al 
identificar patrones complejos y relaciones no evidentes en los datos, sino que 
también reducen significativamente los tiempos de diagnóstico, permitiendo 
intervenciones tempranas. 

---

## Objetivos del proyecto
Explorar y limpiar un dataset clínico relacionado con PCOS.
Construir y comparar modelos supervisados para predecir la presencia de PCOS.
Evaluar modelos con métricas relevantes (Accuracy, Precision, Recall, F1, AUC-ROC).
Identificar variables con mayor poder predictivo.
Proveer visualizaciones y reportes para interpretación clínica y técnica.

---

## Métricas y criterios de evaluación
Accuracy — proporción de predicciones correctas.
Precision — proporción de verdaderos positivos entre las predicciones positivas.
Recall (sensibilidad) — proporción de verdaderos positivos detectados.
F1-Score — media armónica entre precision y recall (utilizada como métrica principal para balance).
AUC-ROC — capacidad discriminativa del modelo.
Además: matriz de confusión, curvas ROC y análisis de coeficientes/support vectors donde aplica.
