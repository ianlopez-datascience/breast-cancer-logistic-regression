Este proyecto implementa un flujo completo de clasificación utilizando el dataset Breast Cancer Wisconsin de Scikit-learn y un modelo de Regresión Logística. 
El objetivo es evaluar el desempeño del modelo mediante diferentes métricas de clasificación, técnicas de validación y métodos de optimización de hiperparámetros.

A lo largo del notebook se realizan las siguientes actividades:

-Carga y exploración del dataset breast_cancer de sklearn.datasets.
-División de los datos en conjuntos de entrenamiento y prueba.
-Entrenamiento de un modelo de Regresión Logística.
-Generación e interpretación de la Matriz de Confusión.
-Cálculo de métricas de evaluación:
  -Precisión (Precision)
  -Recall
  -F1-Score
  -AUC-ROC
-Aplicación de K-Fold Cross-Validation con k=5 y k=10 para comparar la estabilidad del modelo.
-Optimización del hiperparámetro C mediante GridSearchCV y RandomizedSearchCV.
-Análisis del impacto de diferentes umbrales de decisión sobre las métricas de clasificación, evaluando el compromiso entre precisión y recall.
